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
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 100%

---

# Résolution des problèmes du [!UICONTROL Panneau de contrôle]

## Connexion et page d&#39;accueil

### Symptôme : impossible de se connecter à Experience Cloud

**Solution :**
L&#39;utilisateur doit rechercher l&#39;ID d&#39;organisation IMS (xxx). L&#39;administrateur doit ajouter l&#39;utilisateur au profil de produit « Campaign-xxx-Admins » pour chaque instance qu&#39;il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : dans la page d’accueil Experience Cloud, les liens permettant d’accéder au [!UICONTROL Panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
un utilisateur ne verra pas les liens tant qu’il n’aura pas été ajouté en tant qu’utilisateur au profil de produit _Campaign-xxx-Administrators/Admin_.

**Solution :**
l’administrateur doit ajouter l’utilisateur au profil de produit _Campaign-xxx-Admins_ pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit s’ajouter en tant qu’utilisateur.

### Symptôme : une instance n’est pas répertoriée dans le [!UICONTROL Panneau de contrôle]

**Cause :****
l’utilisateur doit probablement être ajouté en tant que profil de produit utilisateur _Campaign-xxx-Administrators/Admin_ pour l’instance qui est absente.

**Solution :**
l’administrateur doit ajouter l’utilisateur au profil de produit _Campaign-xxx-Admins_ pour chaque instance qu’il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;&quot;utilisateur&quot;.

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/34941?learn=on&captions=fre_fr){transcript=true}

*Vérifier l’ID IMS Org (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/34775?learn=on&captions=fre_fr){transcript=true}

*Comment ajouter un administrateur aux administrateurs de profil de produit pour pouvoir utiliser le [!UICONTROL Panneau de contrôle] (01:03 min)*

### Documentation utile

* [Découverte du Panneau de contrôle](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
* [[!UICONTROL Gestion des autorisations pour le Panneau de contrôle]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert les actions suivantes :

* [!UICONTROL Ajout à la liste autorisée] de l&#39;adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Paire de clés privée/publique devant être enregistrée auprès d’Adobe Campaign
* Pour vous connecter directement au serveur SFTP, vous aurez également besoin du logiciel client SFTP

### Documentation utile {#helpful-docs}

* [Connexion à votre serveur SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
