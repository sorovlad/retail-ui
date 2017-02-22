# Changelog

### 0.6.12 -> 0.6.13
- DatePicker - добавлен пропс onUnexpectedInput и оптимизированы вызовы onFocus, onBlur и onChange
- RadioGroup - поправлена работа пропса renderItem
- Dropdown, Select - добавлены пропсы maxMenuHeight, disablePortal
- ScrollContainer - установлена минимальная высота ползунка скролбара
- Tooltip - учитывает клики по элементам портала

### 0.6.11 -> 0.6.12
Поправлена ошибка при деплое

### 0.6.10 -> 0.6.11
Обновлены для соответстивая гайдам:
- Radio [153400aa48f552a17a9bea4e86f13b2a947af5a1]
- RadioGroup [153400aa48f552a17a9bea4e86f13b2a947af5a1]
- DatePicker [0bbe9757e385994705e21f0b6ca291a8b740b6f9]

Button - добавлен параметр `arrow` включающий отображение стрелки [77d35434c09254c05ec0eeff9063b27fa18f6f10]

Поправлен вызов метода `blur` у `document.body` при клике на кнопку или ссылку [a5caa6eed8a45dd04dcf7f7fedee20e6f26f71d2]