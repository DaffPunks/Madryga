## Шифр Мадриги

Для начала ты должен добавить эти строки перед концом <body></body> в ".html" файл 

``
<script src="src/jquery.js" type="text/javascript"></script>
<script src="src/main_work.js" type="text/javascript"></script>
``

И добавить это в <body></body>

## Для шифрования

``
// Текст для шифра
<textarea rows="10" cols="100" id="en_text"></textarea>
// Ключ для шифра
<input id="en_cypher">
// Кнопка
<button id="en_btn">Зашифровать</button>
``

## Для расшифрования

``
// Текст для шифра
<textarea rows="10" cols="100" id="de_text"></textarea>
// Ключ для шифра
<input id="de_cypher">
// Кнопка
<button id="de_btn">Зашифровать</button>
``