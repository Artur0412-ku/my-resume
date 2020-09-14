## Подключение формы обратной связи

### Поле ввода телефона
1. Поменять атрибут `placeholder="Phone"` на  `placeholder="+38 (0__) ___-__-__"` в `input` с номером телефона
2. Добавить `id="callback-form-tel-input"` на `input` с номером телефона
3. Убрать атрибут `pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"`

### Поле ввода имени
4. Добавить `id="callback-form-name-input"` на `input` с именем

### Поле ввода почты
5. Добавить `id="callback-form-email-input"` на `input` с почтой

### Форма
6. Добавить `id="callback-form"` на `form` тег со всеми `input`

### Модалка 

7. Добавить `id="request-received"` на модалку request-received

### Добавление стилей ошибки валидации
8. Добавить в `style.css` класс `input-error-border` со стилем `border: 1px solid red;` ПОСЛЕ класса `callback-form-input`


### Подключение скрипта

9. Скопировать скрипт `callback-form.js` в папку `js`
10. Подключить скрипт `callback-form.js` перед закрывающим тегом `</body>`
11. Протестить что форма работает

