---
title: так само, як ім'я файлу краще
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e2dcca1295e37007593b34c2d818ad1d1133e4a1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676554"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Обов'язковий Алхімія заголовок H1, H2's не працюють.
Кращі практики та керівні принципи для алхімії авторська:

1. **Чи не гніздо Алхімія розуміння в папках**-це буде порушувати структуру URL. Ми дивимося в фіксації цього.
1. Файли в папці **AlchemyInsights** повинні мати імена нижнього регістру з дефісами для пробілів EX. ***як увімкнути-Судова практика-Hold***.
    1. Додайте ІДЕНТИФІКАТОР правила або код ковша з [порталу Алхімія партнера](https://alchemyportal.azurewebsites.net) в полі MS. Custom. Колишній. ***г. Custom: 100021***
1. Використайте решту метаданих у верхній частині цього файлу як шаблон.
1. В [Алхімія партнера порталу](https://alchemyportal.azurewebsites.net), перейдіть до розділу **Insight назва клієнта:** і використовувати це як відправну точку для вашого H1 заголовок для Insight. 
    > [!NOTE]
    > Алхімія статистика повинна мати тільки один H1 у верхній або вони будуть ламатися у виробництві. H2s не відтворювати або використовувати **сміливі** або інші правила для позначення окремих розділів.
1. Потім заповніть текст тіла за допомогою чернетки матеріалу в розділі "аналітичні огляди клієнтів" на сторінці правила Алхімія
    1. Маркіровані списки є штраф
    1. Нумеровані списки
    1. **Жирним шрифтом** і *курсивом* є OK
    1. Посилання завжди повинні бути або **"посилання на веб"/зовнішні** або **глибокі посилання на елементи призначеного для користувача інтерфейсу**, а не внутрішні посилання.
    1. Фотографії офіційно не підтримуються в цей час, але це на дорожню карту.

І це дійсно вже трохи занадто довго. Краща практика становить близько 400 символів---------------------------------

Після того, як ваш контент буде готовий, витягніть його в живу гілку. Потім перейдіть до [Алхімія партнера порталу](https://alchemyportal.azurewebsites.net) і введіть ім'я файлу в поле URL. 