---
title: ЗВД правило для США/Великобританія номер паспорта не працює
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 3d3b7dc2d9510376bc9eef6ec69b87ad7c681b05
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507319"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Проблеми з ЗВД-US/Великобританія номери паспорта

**Важливо**: у ці безпрецедентні часи ми докладаємо всіх зусиль до того, щоб служби SharePoint Online і OneDrive були завжди доступні. Докладні відомості надано у статті [Тимчасові коригування функцій SharePoint Online](https://aka.ms/ODSPAdjustments).

**ЗВД проблеми з US/Великобританія номери паспорта**

У вас виникли проблеми з **запобігання втрати даних (звд)** не працює для вмісту, що містить **номер ПАСПОРТА США/uk** при використанні типу Звд тип інформації в O365? Якщо це так, переконайтеся, що вміст містить потрібну інформацію про те, що в політиці ЗВД шукає, коли його оцінено.
  
Наприклад, для **американського/Великобританії номер паспорта** політики, налаштовані з довірчий рівень 75%, нижче оцінюються і має бути виявлено правило, щоб ініціювати
  
- **[Форматі:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** Дев'ять цифр

- **[Візерунок:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** Дев'ять цифр поспіль

- **[Контрольна сума:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ні, немає контрольної суми

- **[Визначення:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-77)** ЗВД політика 75% впевнений, що він виявлений цей тип конфіденційної інформації, якщо в безпосередній близькості від 300 символів:

  - Функція Func_usa_uk_passport знаходить вміст, який відповідає шаблону.

  - Знайдено ключове слово з Keyword_passport.

    Наприклад, наступний зразок буде ініціювати для **США/Великобританія паспорт номер** політики: американський паспорт номер 123456789

Для отримання додаткової інформації про те, що потрібно для США/Великобританія номер паспорта, який буде виявлений для вашого контенту, див в наступному розділі в цій статті: [які типи конфіденційної інформації Шукайте нас/номер ПАСПОРТА Великобританії](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us--uk-passport-number)
  
Використовуючи інший вбудований тип конфіденційної інформації, зверніться до такої статті, щоб отримати відомості про те, що потрібно для інших типів: [які типи конфіденційних даних шукають](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  