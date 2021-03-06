---
title: Усунення несправностей із зарахування пристроїв Windows у корпорації Майкрософт Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: 7b298360fe31d3f52ef382e5b8f25ee3588c36c8
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 08/29/2019
ms.locfileid: "36665853"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Усунення несправностей із зарахування пристроїв Windows у корпорації Майкрософт Intune

Огляд ресурсів, перераховані нижче, щоб вирішити проблему, ваш тепер.
  
Деякі поширені повідомлення про помилки та резолюції кроки:
  
 **Не вдалося інсталювати програмне забезпечення, 0x80cf4017:** Ваш обліковий запис сертифіката закінчився. Повторно завантажити пакет програмного забезпечення ПК клієнта в консолі адміністратора Intune. Огляд цієї документації для отримання додаткової інформації.
  
 **Код помилки 0x801c0003:** Помилка може виникнути у таких випадках:
  
-  Користувач має додаткові пристрої вступив ніж пристрою обмеження. Перегляньте ці документи до [зняття пристрою](https://docs.microsoft.com/intune/devices-wipe) або [Змінити обмеження на пристрій](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).

-  "Користувачі можуть приєднатися до пристроїв блакитні об'яви" встановлено значення "немає". Встановіть його на всіх, або виберіть користувачів. Огляд [цієї документації](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) для отримання додаткової інформації.

-  Пристрою вже зареєстровано іншим користувачем. Якщо це так, видалити пристрій з Azure Intune консоль або вручну unenroll пристрій, перш ніж повторити спробу.

-  Становить 10 Windows Home. Тільки Windows 10 Pro, освіти та рішенню щодо підприємства можуть приєднатися до Azure Active Directory.

Додаткові ресурси, щоб допомогти вирішити вашу проблему:
  
-  Використовувати [Intune виправлення неполадок портал](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) діагностувати та усунути поширені зарахування невдач. Огляд [цей документ](https://docs.microsoft.com/intune/help-desk-operators) для більш докладної інформації.

-  Перегляньте ці документи список поширених помилок, які заважають заявки на участь та постанов до кожного: [усунення несправностей керівництво](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) та [усунення несправностей doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).

[Дізнайтеся, як записатися пристроїв Windows у корпорації Майкрософт Intune](https://docs.microsoft.com/intune/windows-enroll).
