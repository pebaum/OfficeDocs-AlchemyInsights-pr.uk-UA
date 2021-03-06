---
title: Проблеми з МЗС
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: a415116b9ba437cb13426896119cd1b40d9ab491
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768858"
---
# <a name="issues-with-azure-mfa"></a>Проблеми з МЗС Azure
Є кілька речей, щоб перевірити, якщо користувачі не можуть увійти в систему за допомогою багатофакторної аутентифікації (МЗС)

1. Відповідного користувача може бути заблоковано на порталі Azure Active Directory. Якщо це так, спроби автентифікації для конкретного користувача будуть автоматично відхилені. [Будь ласка, виконайте дії, описані в цій статті, щоб розблокувати їх.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Якщо розблокування користувача не допомогло, або користувач не заблоковано, можна спробувати скинути МЗС для користувача, і вони будуть проходити процес зарахування знову. [Будь ласка, дотримуйтесь інструкцій, наведених у цій статті.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

Якщо це перший раз, коли ви ввімкнули МЗС і ваші користувачі не в змозі увійти в систему не браузерів, таких як Outlook, Skype і т. д., можливо, ADAL (Active Directory автентифікації бібліотека) не включений на вашу передплату O365. У цьому випадку вам потрібно буде підключитися до Exchange Online PowerShell і запустити цю команду:  *Set-Організаціїconfig-OAuth2ClientProfileEnabled: $TRUE*