---
title: Ajouter des certificats SSL
description: Découvrez comment ajouter des certificats SSL pour sécuriser vos sous-domaines.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
TQID: https://experienceleague.adobe.com/0bt8fHWusGHKrXc-ireqA25Eo75SA2pCj9MhADcHBxA
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2: id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
source-git-commit: 9b8483fbaa7dce7f908c79e929d3b9628fd8fa44
workflow-type: tm+mt
source-wordcount: 288
ht-degree: 100%

---

# Ajouter des certificats SSL

Le [!UICONTROL Panneau de contrôle] d’Adobe Campaign permet d’ajouter des certificats SSL pour sécuriser vos sous-domaines.

## Accès à la gestion des sous-domaines dans le Panneau de contrôle

Pour accéder à la gestion des sous-domaines dans le Panneau de contrôle, rendez-vous sur :

* [Accueil Experience Cloud](https://experience.adobe.com/#/home) > Sélecteur de solution : **[!DNL Campaign]** > Carte **[!UICONTROL Panneau de contrôle]** > Carte **[!UICONTROL Sous-domaines et certificats]**

  ou
* Directement à partir de l’URL : [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Étapes pour ajouter des certificats SSL

Pour ajouter des certificats SSL, trois étapes sont nécessaires :

### &#x200B;1. Générer les demandes de signature de certificat

La demande de signature de certificat (CSR) est nécessaire pour l’achat d’un certificat SSL. Elle doit être générée pour l’instance et les sous-domaines que vous prévoyez de sécuriser.

La vidéo ci-dessous montre comment générer une demande de signature de certificat dans le panneau de contrôle.

>[!VIDEO](https://video.tv.adobe.com/v/31317?learn=on){transcript=true}

*Générer les demandes de signature de certificat (02:36 min)*

>[!NOTE]
>
>Plusieurs améliorations ont été apportées au processus de génération de CSR :
>
>* Lors de la génération d’une demande de signature de certificat, vous pouvez désormais sélectionner l’un des sous-domaines inclus comme nom commun.
>* Vous pouvez désormais copier le résumé de la demande de signature de certificat avant de la générer.
>* Une fois qu’une demande de signature de certificat a été générée, vous pouvez la télécharger de nouveau à partir des logs de traitement. Cette fonctionnalité ne s’applique pas aux certificats générés avant cette version.
>
>![Télécharger la CSR](/help/assets/download-csr.gif)
>
>Consulter la [documentation du produit](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=fr) pour en savoir plus.
>

### &#x200B;2. Acheter un certificat SSL

Après avoir obtenu la demande de signature de certificat, vous devez acheter le certificat SSL auprès d’une autorité de certification approuvée par votre organisation.

### &#x200B;3. Installer des certificats SSL

Une fois que vous avez obtenu le certificat SSL, il doit être installé pour les sous-domaines que vous envisagez de sécuriser.

La vidéo ci-dessous montre comment installer des certificats SSL dans le [!UICONTROL Panneau de contrôle].

>[!VIDEO](https://video.tv.adobe.com/v/31166?learn=on){transcript=true}

*Installer des certificats SSL (01:25 min)*


