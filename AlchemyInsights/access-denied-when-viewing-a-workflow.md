---
title: Відмовлено в доступі під час перегляду робочого процесу
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: c576bf88225582f2577e0b59506a7482cf9f38d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687351"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Відмовлено в доступі під час перегляду робочого процесу

SharePoint 2013 робочих циклів, які намагаються надіслати повідомлення електронної пошти до групи SharePoint може не з повідомлення про помилку "немає доступу", якщо членство групи SharePoint не встановлено для всіх.
  
 **Щоб вирішити цю проблему, виконайте такі дії:**
  
 1. Дозволити всім користувачам бачити учасників групи SharePoint.
  
 2. Видалити групу SharePoint, з до або копія рядок повідомлення електронної пошти.
  
 3. Явно додати користувачів до рядка кому або копія, якщо видимість членства не можна змінити для групи SharePoint.
  
Для перегляду більш детальної інформації, будь ласка, зверніться до [http несанкціонованого доступу до/_vti_bin/Client.SVC/SP.utilities.Utility.sendemail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  