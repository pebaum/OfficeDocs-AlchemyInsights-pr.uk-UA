---
title: Моніторинг умовного доступу
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 8b76d58791408037b5704b421d7afa166e3ea0be
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713739"
---
# <a name="monitoring-conditional-access-for-exchange"></a>Моніторинг умовного доступу для Exchange

Користувачі, націлені з умовним доступом, отримають сповіщення електронною поштою, якщо вони не відповідають вимогам до вашої організації. Щоб вирішити проблему, рекомендовано один або кілька таких рішень:
  
- Якщо пристрій передбачається Зарахованим, порадьте користувачеві перейти до програми порталу компанії і переконатися, що вона з'являється на порталі компанії. Якщо це не так, користувач має зареєструвати пристрій.
    
- На порталі Azure перейдіть до ** \> InTune пристрою відповідності**. У розділі **монітор** натисніть **сумісність пристроїв**. Перегляньте звіт про відповідність пристрою, щоб перевірити, чи пристрій користувача позначено як сумісний. 
    
- На порталі Azure перейдіть до ** \> InTune пристрою відповідності**. У розділі **керування**виберіть пункт **політики**. У списку політики дотримання переконайтеся, що профіль призначено для пристрою користувача. Якщо жоден профіль не призначається, то InTune не зможе підтвердити статус відповідності пристрою. 
    
- Змінити призначення умовного доступу користувача.
    
1. На порталі Azure перейти до **InTune \> умовного доступу \> політики**
    
2. Виберіть політику зі списку
    
3. Натисніть **користувачі та групи**
    
4. Щоб націлити користувача на певну політику, додайте їх до списку **включити** . Щоб переконатися, що користувач пропущено з політики, додайте їх до списку **винятків** . 
    
Докладніше: [як відстежувати пристрої умовного доступу](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)
  

