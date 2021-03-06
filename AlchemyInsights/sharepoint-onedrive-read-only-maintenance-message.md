---
title: Повідомлення лише для читання, під час спроби використання SharePoint або OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 02cf1aa7abae365a3d317af9e785648d1c1517e1
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051302"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a>Повідомлення лише для читання, під час спроби використання SharePoint або OneDrive

Користувачі можуть отримувати повідомлення, **лише для читання** , під час спроби використовувати SharePoint або OneDrive, для одного з таких сценаріїв. 

-   Заплановані або активні обслуговування.  Перевірте їх, перейшовши до [центру повідомлень](https://portal.office.com/adminportal/home#/messagecenter).
-   Високий пріоритет, активний інцидент служби, який може трапитися. Перевірте наявність будь-яких рекомендації/інцидентів, перейшовши до [служби охорони здоров'я](https://portal.office.com/adminportal/home#/servicehealth).
-   Неповнолітній Auto-зцілення сценарій відновлення, який може відбуватися через будь-які несподівані події на серверах, які можуть тривати менше 30 хв або близько того. 
    
    Є немає повідомлення центру або служби охорони здоров'я посад для цих незначних відновлень, але ви повинні повернутися до нормального найближчим часом.

У дуже небагатьох випадках ми спостерігали, що один з трьох сценаріїв, перерахованих вище, були причиною, і служба була відновлена, але користувачі кеш браузера не був очищений.

Перш ніж перейти на сайт, спробуйте очистити кеш браузера.

1. У браузері Microsoft EDGE виберіть **настройки**, а потім виберіть **конфіденційність і безпека**.
2. У розділі **Очистити перегляд**виберіть елемент **вибрати, що слід очистити**.
3. Виберіть **файли cookie та збережені дані веб-сайтів**, а потім виберіть **Очистити**.

>[!Note] 
> Ці дії можуть відрізнятися під час використання інших браузерів, таких як Mozilla Firefox або Google Chrome.

>[!Note] 
> Іншим варіантом було б відкрити ваш сайт SharePoint або OneDrive у новому вікні InPrivate.