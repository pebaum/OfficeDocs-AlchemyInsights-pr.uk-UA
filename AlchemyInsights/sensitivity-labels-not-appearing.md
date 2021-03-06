---
title: Не відображаються позначки чутливості
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 1326eca02044014a8e9c072fcc3e4cd3a41c7a9f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511673"
---
# <a name="sensitivity-labels-not-appearing"></a>Не відображаються позначки чутливості

За допомогою міток чутливості можна класифікувати та захищати вміст делікатного характеру. Вони можуть бути створені в Microsoft 365 центр відповідності, Microsoft 365 Центр безпеки, або Microsoft 365 безпеки & центр відповідності класифікації > чутливість етикетки. Щоб дізнатися більше про цю функцію, перегляньте [Огляд міток чутливості](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).

Якщо ви налаштували Мітки чутливості, але вони не відображаються в застосунках Office, перевірте наступне:

- Переконайтеся, що підпис чутливості [Опубліковано](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels#what-label-policies-can-do) користувачам і групам, які ви хочете.

- Переконайтеся, що користувач використовує програму, яка [підтримує Мітки чутливості-див.](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable)

- Якщо ви [переміщуєте підписи захисту інформації до Azure](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), зверніть увагу на міркування, перелічені [тут](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).

- Підтримка запобігання втраті даних (ЗВД): наразі лише підписи збереження можуть використовуватися як умова в політиці ЗВД.  Підтримка Мітки чутливості у ЗВД політика ще недоступна, але ми працюємо над цим.

- Коли шифрування ввімкнено для Мітки чутливості, ви можете вибрати один із таких:
    - Призначити дозволи зараз
    - Дозволити користувачам призначати дозволи


Щоб отримати додаткові відомості про можливі проблеми, перегляньте [відомі проблеми з мітками чутливості](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).