---
title: Потрібна допомога в електронній пошті обмеження відправки?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002938"
- "5630"
ms.openlocfilehash: 7f563df313c869d18c3e4240d271c649a74914af
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 05/20/2020
ms.locfileid: "44358362"
---
# <a name="need-help-with-email-sending-limits"></a>Потрібна допомога в електронній пошті обмеження відправки?

Нижче знаходиться **по-дизайн відправки лімітів** , що застосовуються в сервісі. Більш детальну інформацію про ці обмеження описано [тут](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).

- Для запобігання доставки небажаних масових повідомлень, ми застосовуємо для кожного користувача **обмеження частоти для всіх вихідних і внутрішніх повідомлень**. У всіх SKUs це обмеження **10 000 одержувачів на день**.  Клієнти, яким потрібно надсилати легальний обсяг комерційної електронної пошти (наприклад, інформаційні бюлетені для клієнтів), повинні використовувати сторонні постачальники, які спеціалізуються на цих службах.
    - **Примітка**: після того, як обмеження частоти одержувачів досягнуто, повідомлення не надсилатимуться з поштової скриньки, доки кількість одержувачів, які було надіслано повідомлення за останні 24 годин, опускається нижче межі. Користувач не зможе надсилати повідомлення до цього моменту.
- Обмеження швидкості повідомлення **30 повідомлень на хвилину** застосовується по всіх skus. Це визначає, скільки повідомлень користувач може надсилати зі свого облікового запису Exchange Online протягом указаного періоду.
- **Максимальна кількість одержувачів, дозволених у полях Кому, копія та Прихована копія** для окремого повідомлення електронної пошти, у всіх skus, є **1000 одержувачів**. Щоб налаштувати цю межу, перейдіть [сюди](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).
