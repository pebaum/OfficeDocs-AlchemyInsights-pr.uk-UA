---
title: 902 (помилки синхронізації через дублювання об'єктів)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: eac74a6d4de58c9cdbdc8e8df8f705293bb12e87
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/22/2019
ms.locfileid: "30781282"
---
# <a name="sync-errors-due-to-duplicate-objects"></a>Помилки синхронізації через дублікати об'єктів

Ви можете отримати одне з таких повідомлень про помилку, після завершення синхронізації каталогів:
  
- Не вдалося оновити цей об'єкт Microsoft Online Services, тому що такі атрибути, пов'язані з цим об'єктом є значення, які вже можуть бути пов'язані з іншого об'єкта в поточному каталозі.
    
- Синхронізовані об'єкта з однаковою адресою проксі уже існує у вашому каталозі Microsoft Online Services.
    
- Не вдалося оновити цей об'єкт, тому що такі атрибути, пов'язаними з об'єктом є значення, які вже можуть бути пов'язані з іншого об'єкта в місцевих каталог послуг: UserPrincipalName.
    
Щоб виявити й усунути проблему, завантажте та запустіть [IdFix DirSync помилка виправляти інструмент](https://www.microsoft.com/download/details.aspx?id=36832).
  
Докладніше перегляньте [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).
  
