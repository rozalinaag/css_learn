# Глава 4
## Механизм наследования стилей

> Наследование - это прием, с помощью которого свойства, относящиеся к одному элементу веб-страницы, распространяются и на вложенные элементы.

Как правило, свойства, которые затрагивают размещение элементов на страницу (поля, фоновый цвет, границы элементов) не наследуются. 
К одному блоку текста можно применять разное количество стилей. И иногда возникает конфликт, где чаще всего побеждает более специфичный стиль.
Специфичный означает более узконаправленный и близкий к конкретному тегу.

## Исключения механизма наследования

Если бы все друг от друга наследовалось без исключения, то получилась бы каша. Поэтому некоторые вещи не наследуются. 
Чтобы это проверить в коде можно вставить "*", что означает полное наследование всего

```css
p *{
padding-left:20px;
}
```

Внутри текста все элементы, которые были заключены в теги, например strong будут иметь отступ слева от текста