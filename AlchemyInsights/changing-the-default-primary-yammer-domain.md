---
title: Змінення стандартного домену Yammer
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002662"
- "5162"
ms.openlocfilehash: 099feb5c58a2b1068a2ec501ff966c6ac73d804d
ms.sourcegitcommit: 87aa36e3ff4835efb120a320c5169bfa77199ec4
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 05/01/2020
ms.locfileid: "43991332"
---
# <a name="changing-the-defaultprimary-yammer-domain"></a>Змінення стандартного або основного домену Yammer

URL-адреса Yammer містить поточне ім'я основного домену для мережі Yammer. Це ім'я може не збігатися з іменем основного домену, указаним в Office 365 або Azure AD. Існує різниця в поведінці, зумовлена кількістю настроюваних доменів, доданих до клієнта, а також тим, чи Yammer має підтримувану конфігурацію (1 клієнт : 1 мережа або 1:1). Доступна документація щодо [доменів Yammer та Office 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/manage-yammer-domains).

Найпоширеніша причина відображення неприпустимого домену – це існування кількох мереж Yammer, які потрібно об’єднати. [Об’єднання кількох мереж в одну](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks) за допомогою мережевого інструмента перенесення – це важливий перший крок. Виконайте його, перш ніж налаштувати основний домен.

**Немає настроюваних доменів**

Стандартний домен (наприклад, fabrikam.onmicrosoft.com) для нових клієнтів використовуватиметься для Yammer. Основний домен налаштовано як yammer.com/fabrikam.onmicrosoft.com.

**Один настроюваний домен**

Yammer автоматично вибере настроюваний домен (наприклад, fabrikam.com) клієнта як основний домен Yammer. Він має бути налаштований як yammer.com/fabrikam.com. Ця зміна вноситься службою синхронізації домену. Щоб вона набула сили, може знадобитися до 24 годин.

**Кілька настроюваних доменів**

Основний домен Yammer може відрізнятися від стандартного домену клієнта. Оскільки існує кілька настроюваних доменів, Yammer не намагається вгадати правильний. Щоб попросити про змінення імені основного домену на вибраний вами основний домен, необхідно звернутися до служби підтримки.

**Додаткові відомості про неполадки та методи їх виправлення**

У деяких випадках домени може бути переміщено між клієнтами, через що не вдається успішно запустити службу синхронізації домену. Крім відображення неприпустимого основного домену, у вас також можуть виникати проблеми з входом або інші помилки. Щоб вирішити цю проблему, можливо, знадобиться перемістити домени до правильної мережі за допомогою служби підтримки Microsoft. Вирішення цієї ситуації вимагає безпосередньої допомоги та певного часу, особливо за наявності дуже великого списку доменних імен. Зверніться до служби підтримки, щоб отримати допомогу з розв'язання таких проблем.

Під час роботи з агентом підтримки буде перевірено, чи домени підтверджено на клієнті під вашим контролем. Вам можуть задати додаткові запитання для перевірки доменів, якщо їх додано до вашого клієнта, але не перевірено службою DNS. Щоб прискорити процес, переконайтеся, що домени перевірено службою DNS.