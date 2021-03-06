---
title: Визначення зовнішньої електронної пошти пересилання поштових скриньок у журналах аудиту
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 592eb92e4b0fe0f9da2fa20bb93ffa4fbbb76662
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508973"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Визначте, коли зовнішня пересилання електронної пошти налаштовано на поштових скриньках

Під час Microsoft 365 користувача, настроювання зовнішньої електронної пошти пересилання поштової скриньки, діяльність перевіряється, частина командлета **Set-поштової скриньки** . Можна переглянути дії за допомогою пошуку журналу аудиту в центрі підтримки & відповідності.

1. Увійдіть до [Microsoft 365 безпеки & центр відповідності](https://protection.office.com/).

2. Перейдіть на сторінку **Search**  >  **пошуку журналу аудиту** пошуку.

3. Виберіть діапазон дат у полях Дата **початку** та **Дата завершення** . Вам не потрібно вказувати ім'я користувача. Переконайтеся, що поле **справи** налаштовано на **відображення результатів для всіх справ**.

4. Натисніть кнопку **Пошук**.

У результатах пошуку натисніть кнопку **Фільтрувати результати** та введіть **набір-поштову скриньку** у полі фільтр активності. Виберіть запис аудиту в результатах. У спливаючому меню **відомості** натисніть кнопку **додаткові відомості**. Слід звернути увагу на відомості кожного запису аудиту, щоб визначити, чи справа пов'язана з пересиланнею електронної пошти.

- **Об'єктиідентифікатор**: псевдонім значення поштової скриньки, який було змінено.

- **Параметри**: _переадресації_ вказують на цільову адресу електронної пошти.

- **Userid**: користувач, який налаштував пересилання електронної пошти на поштову скриньку, у полі **ідентифікатор об'єкта** .

Для отримання додаткових відомостей див. [визначення, які встановлюють пересилання електронної пошти для поштової скриньки](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).
