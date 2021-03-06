---
title: Create A New Welcome Card
description: Create your own welcome card in the SAP Cloud Platform Mobile Services.
auto_validation: true
primary_tag: products>sap-mobile-cards
tags: [  tutorial>beginner, operating-system>ios, operating-system>android, topic>mobile, products>sap-cloud-platform, products>sap-mobile-cards, software-product-function>sap-cloud-platform-mobile-services ]
time: 10
author_name: Sandeep TDS
author_profile: https://github.com/sandeep-tds
---
## Prerequisites

## Details
### You will learn
- How to create an SAP Mobile Card using SAP Cloud Platform Recipes

---

[ACCORDION-BEGIN [Step 1: ](Get familiar with real world use case)]

An organization wants to share a welcome message to a new employee. Upon successful authentication in the SAP Mobile Cards app, the new employee sees a welcome card. In this card, the organization shows basic details to help the employee have a great first day. This card is available to the user without the user having to subscribe to the card.

Welcome Cards are Server Managed Cards that are automatically subscribed. When such a card is created, users automatically get instances of the card because they are automatically subscribed to the card.

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Create A Welcome Card using Recipes)]

SAP Mobile Cards can be created in multiple ways. In this tutorial, you will create a card using SAP Cloud Platform Recipes.

> SAP Cloud Platform Recipes are sets of guided interactive steps which help you achieve specific goals.

In your web browser, open the [SAP Cloud Platform trial cockpit](https://cockpit.hanatrial.ondemand.com/).

Navigate to the trial global account by clicking **Enter Your Trial Account**.

!![Trial global account](img_8_1.png)

In the side navigation bar, click **Recipes**.

!![CP CF Trial Account](img_8_2.png)

Click the **Build a Micro App for SAP Mobile Cards** tile.

!![Recipes View](img_8_3.png)

Go through the details mentioned and click **Start Recipe**.

!![Recipes View](img_8_3_1.png)

In the *Check Prerequisites* tab of the wizard, click **Next**.

!![Booster Wizard Tab 1](img_8_4.png)

In the *Select Subaccount* tab of the wizard, select the following and click **Next**.

|Field|Value|
|----|---|
|Subaccount| trial |
|Space| dev |

!![Booster Wizard Tab 2](img_8_5.png)

> If your Mobile Card Kit status is not **Available** please complete the [previous tutorial](https://developers.sap.com/tutorials/cp-mobile-cards-setup.html) in this mission.

In the *Select Cards* tab of the wizard, select the **Sample Template Welcome Card** and click **Next**.

!![Booster Wizard Tab 3](img_8_6.png)

In the *Configure Cards* tab of the wizard, enter the name as following and click **Next**.

|Field|Value|
|----|---|
|Name| Recipe Welcome Card |

!![Booster Wizard Tab 4](img_8_7.png)

In the *Review* tab of the wizard, review the details you've entered and click **Finish**.

!![CPMS cockpit with 2 cards](img_8_8.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 3: ](View the Created Card in Mobile Services Cockpit)]
Log into SAP Cloud Platform Mobile Services cockpit and navigate to **SAP Mobile Cards** to look into the Mobile Cards configuration.

!![MobileCards](img_1.png)

In the SAP Cloud Platform Mobile Services Cockpit, you will now see the *Recipe Welcome Card* we have created.

!![Booster Wizard Tab 5](img_8_9.png)

[VALIDATE_2]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 4: ](View the Welcome Card in Mobile Cards Client)]

>Make sure you are choosing the right device platform tab ( **Android** or **iOS** ) **above**.

Welcome cards are auto subscribed by default and downloaded automatically after registration.

You should see two Welcome Card in your Mobile application. One created through the cockpit, and the other created using SAP Cloud Platform Recipes for SAP Mobile Cards.

> To view the card immediately, perform a pull refresh.

[OPTION BEGIN [Android]]

!![MobileCards](img_9.png)

[OPTION END]

[OPTION BEGIN [iOS]]

!![MobileCards](img_10.png)

[OPTION END]

You can now view your first SAP Mobile card on the device.

**Congratulations!** You have learnt how to create an SAP Mobile Card using a Recipe. In the [next tutorial](https://developers.sap.com/tutorials/cp-mobile-cards-automatic-instance-generation.html) you will learn how to create the card manually.


[DONE]
[ACCORDION-END]
