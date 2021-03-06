---
title: Помилка під час надсилання електронної пошти заблоковано Спадхаус
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714279"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Помилка під час надсилання електронної пошти: клієнт хоста заблоковано за допомогою Спадхаус

IP-адреса, яка надіслала повідомлення, знаходиться на блоці списку, який належить [Спадхаус](https://go.microsoft.com/fwlink/p/?linkid=123245). Причини, заблоковані Спаміхаус включають скомпрометовані облікові записи, скомпрометовані машини, що спільний доступ до публічної IP-адреси та політики інтернет-провайдера (ISP). Можливі виправлення:
  
- Для заблокованих вхідних повідомлень, де ви керуєте вихідним сервером електронної пошти, вам потрібно визначити причину і видалити блок з сайту Спадхаус.

- Для заблокованих вхідних повідомлень, де Вихідна IP-адреса належить комусь іншому, власник адреси повинен видалити блок з веб-сайту Спадхаус. Якщо IP-адресу, що знаходиться у списку політики блокування (PBL), власник може призначити іншу статичну IP-адресу або видалити адресу з PBL.

- Для заблокованих вихідних повідомлень з вашого домену, підключеного до корпорації Майкрософт, ви можете отримати цю помилку, якщо повідомлення направляються через сторонній сервіс. Ви можете скористатися інструментом підстановки WHOIS, щоб знайти власника заблокованої IP-адреси.
