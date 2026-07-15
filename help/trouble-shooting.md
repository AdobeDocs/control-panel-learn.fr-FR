---
title: Résolution des problèmes du Panneau de contrôle
description: Découvrez comment résoudre les problèmes liés au Panneau de contrôle.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
TQID: https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2: id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
source-git-commit: 9b8483fbaa7dce7f908c79e929d3b9628fd8fa44
workflow-type: ht
source-wordcount: 353
ht-degree: 100%

---

# Résolution des problèmes du [!UICONTROL Panneau de contrôle]

## Connexion et page d&#39;accueil

### Symptôme : impossible de se connecter à Experience Cloud

**Que faire :**
L’utilisateur ou l’utilisatrice doit rechercher l’ID d’organisation IMS (xxx).L&#39;administrateur doit ajouter l&#39;utilisateur au profil de produit « Campaign-xxx-Admins » pour chaque instance qu&#39;il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : dans la page d&#39;accueil Experience Cloud, les liens permettant d&#39;accéder au [!UICONTROL Panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
Les liens ne sont pas visibles tant que les personnes n’ont pas été ajoutées en tant qu’utilisateurs et utilisatrices au profil de produit _Campaign-xxx-Administrators/Admin_.

**Que faire :**
L’administrateur ou l’administratrice doit ajouter l’utilisateur ou l’utilisatrice au profil de produit _Campaign-xxx-Admins_ pour chaque instance à gérer.Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : une instance n&#39;est pas répertoriée dans le [!UICONTROL Panneau de contrôle]

**Cause :**
La personne doit probablement être ajoutée en tant que profil de produit *utilisateur ou utilisatrice* _Campaign-xxx-Administrators/Admin_ pour l’instance manquante.

**Que faire :**
L’administrateur ou l’administratrice doit ajouter l’utilisateur ou l’utilisatrice au profil de produit _Campaign-xxx-Admins_ pour chaque instance à gérer.Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;&quot;utilisateur&quot;.

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*Vérifier l’identifiant d’organisation IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*Comment ajouter un administrateur ou une administratrice à l’équipe d’administration du profil produit pour pouvoir utiliser le [!UICONTROL Panneau de contrôle] (01:03 min)*

### Documentation utile

* [Découvrir le panneau de contrôle](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
* [Gestion des autorisations pour le [!UICONTROL Panneau de contrôle]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert les actions suivantes :

* [!UICONTROL Ajout à la liste autorisée] de l&#39;adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Paire de clés privée/publique devant être enregistrée auprès d&#39;Adobe Campaign
* Pour vous connecter directement au serveur SFTP, vous aurez également besoin du logiciel client SFTP

### Documentation utile {#helpful-docs}

* [Connexion à votre serveur SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
