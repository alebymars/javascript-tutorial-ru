Алгоритм решения такой.

Только численный ввод в поле с суммой разрешаем, повесив обработчик на `keypress`.

Отслеживаем события изменения для перевычисления результатов:

- На `input`: событие `input` и дополнительно `propertychange/keyup` для совместимости со старыми IE.
- На `checkbox`: событие `click` вместо `change` для совместимости с IE8-.
- На `select`: событие `change`.
