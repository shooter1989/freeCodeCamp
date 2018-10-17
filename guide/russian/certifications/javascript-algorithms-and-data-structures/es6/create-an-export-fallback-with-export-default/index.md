---
title: Create an Export Fallback with export default
localeTitle: Создание экспортного возврата с экспортом по умолчанию
---
## Создание экспортного возврата с экспортом по умолчанию

Что такое запасная стоимость? В основном по умолчанию код будет возвращаться, если ничего не было установлено. Например, переменные имеют значение возврата по умолчанию для `undefined` . Это, как говорится, намек на этот вызов!

## Подсказка 1:

Просто добавьте `export default` в начало функции.

## Оповещение о спойлере - решение впереди!

## Решение:

```javascript
"use strict"; 
 export default function subtract(x,y) {return x - y;} 

```