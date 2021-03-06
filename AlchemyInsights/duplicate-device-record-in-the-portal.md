---
title: Повторюваний запис пристрою на порталі
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790178"
---
# <a name="duplicate-device-record-in-the-portal"></a>Повторюваний запис пристрою на порталі

Якщо пристрій неналежно повідомляє сайту диспетчера конфігурацій стан спільного керування, на порталі може відображатися 2 записи пристрою. Щоб перевірити стан спільної керування на пристрої, ознайомтеся зі стовпцем **Спільне керування** для пристрою в консолі диспетчера конфігурацій. Якщо стовпець не відображається, його можна додати, клацнувши правою кнопкою миші будь-який заголовок стовпця та вибравши його зі списку.

Значення параметра "Спільне керування" має бути **Так**. Якщо параметр має значення **Ні**, відкрийте аплет клієнта диспетчера конфігурацій на клієнтському пристрої та встановіть прапорець для властивості **Спільне керування** на вкладці "Загальне".

- Якщо параметр має значення **Увімкнуто**, це вказує на проблеми з клієнтським зв’язком з точкою керування. Ознайомтеся з **CcmMessaging. log** на пристрої, щоб дослідити потенційні проблеми з підключенням.

- Якщо параметр має значення **Вимкнуто**, а пристрій зареєстровано в Inteune, переконайтеся, що цей пристрій одержав політику спільного керування, переглянувши **Comeanemempentandler.log** на пристрої.
