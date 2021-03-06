---
title: 1336 відновлення папки елементів заповнено
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 4f0cba480fcc05114abd8f370b84e9a37e5f2804
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510773"
---
# <a name="the-recoverable-items-folder-is-full"></a>Папка «Відновлювані елементи» заповнено

Для поштових скриньок Exchange Online обмеження сховища за промовчанням для папки «Відновлювані» становить 30 ГБ. Граничний обсяг сховища для папки «Відновлювані елементи» автоматично збільшується до 100 ГБ, якщо поштова скринька розміщується на судовому утриманні, пошук необхідної інформації, або призначається політиці збереження.

Після того, як Відновлювані елементи папки, досягає обмеження на зберігання, функції поштової скриньки, що впливає таким чином:

- Користувач не може видалити елементи з поштової скриньки.

- Помічник із керованих папок не може видалити елементи на основі тегу збереження або параметрів керованих папок.

- Для поштових скриньок, які мають один елемент відновлення ввімкнуто, або розміщені на утримання, копіювання та записування сторінки процес захисту не може підтримувати версії елементів, які редагується користувачем.

- Для поштових скриньок, які мають журналювання аудиту поштової скриньки, не можна зберегти записи журналу аудиту поштової скриньки в папці «Відновлювані» папки перевірки.

Для поштових скриньок, які не є утримувані, адміністратори можуть використовувати `Search-Mailbox -SearchDumpsterOnly -DeleteContent` команду в Exchange Online PowerShell для видалення елементів у папці «Відновлювані елементи». Для отримання додаткових відомостей зверніться до таких розділів:

- [Як шукати й видаляти повідомлення](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [Пошук-поштову скриньку](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

Для поштових скриньок, які знаходяться на утриманні, адміністратори повинні видалити утримання, перш ніж вони зможуть видалити елементи з папки "Відновлювані". Для отримання додаткових відомостей див. [видалення елементів у папці «Відновлювані елементи» на основі хмарних поштових скриньок](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Щоб запобігти повному відновленню папки «Відновлювані», адміністратори можуть збільшити обмеження сховища для папки «Відновлювані» для поштових скриньок, які потрібно утримувати, і настроїти політику збереження поштової скриньки, яка переміщує елементи з папки «Відновлювані елементи» до архівної поштової скриньки користувача. Переглянути [, як збільшити квоту видобутих елементів для поштових скриньок](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold), які призупинено.
