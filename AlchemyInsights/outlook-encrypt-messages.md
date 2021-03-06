---
title: S/MIME у програмі Outlook на веб-сайті
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 6bbbf8722dacb8b7d5191d57ce1055a48dcb4dd0
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511529"
---
# <a name="encrypt-email-messages-in-outlook"></a>Шифрувати повідомлення електронної пошти в Outlook

Microsoft 365 повідомлення шифрування, побудована на Microsoft Azure прав керування (Azure RMS), який входить до складу Azure відомості про захист. Якщо ваша підписка включає керування правами Azure або захист інформації в Azure, **не потрібно виконувати жодних дій, щоб вручну увімкнути або активувати** службу керування правами.

На основі відгуків клієнтів ми більше не вмикаємо правила потоку Exchange Mail, щоб автоматично шифрувати вихідне повідомлення електронної пошти, що містить певний тип конфіденційної інформації у вашому клієнті за промовчанням. Замість цього, ми надаємо докладні інструкції про те, як ви можете зробити це самі. Додаткові відомості про створення правила транспортування для шифрування конфіденційної інформації наведено в [цій статті](https://aka.ms/OmeEtr).

- У разі використання Outlook на веб-сайті (раніше **OWA**): при складанні повідомлення електронної пошти, просто натисніть кнопку **захистити** в owa. Це застосує дозвіл "не пересилати". Натисніть **змінити дозвіл** і виберіть **шифрувати** , щоб зашифрувати повідомлення.

- Якщо використовується **клієнт Outlook**: надіслати зашифроване повідомлення з Outlook 2013 або 2016 або Outlook 2016 для Mac, виберіть **Параметри**  >  **дозволи**, а потім виберіть потрібний параметр захисту.

- Щоб **автоматично шифрувати всі повідомлення** , надіслані певним одержувачам або зовнішнім партнерським організаціям, потрібно створити правило транспортування пошти в центрі адміністрування Exchange. Докладні інструкції наведено в [цій статті підтримки](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email#create-mail-flow-rules-to-encrypt-email-messages-with-the-new-ome-capabilities).

