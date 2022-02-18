# WebFont Exo 2

Пакет для установки веб-шрифта: Exo 2.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-exo2
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-exo2": "github:getscope/npm-webfont-exo2"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Exo 2', sans-serif;
}
```

Для импорта веб-шрифта в `SCSS`, Вы можете воспользоваться следующими путями:

#### Импорт начертаний `normal` и `italic`

```scss 
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_all-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_all-italic.scss";
```

#### Импорт начертаний `normal`

```scss 
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_100-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_200-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_600-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_800-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_900-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_all-normal.scss";
```

#### Импорт начертаний `italic`

```scss 
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_100-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_200-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_300-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_400-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_500-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_600-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_700-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_800-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_900-italic.scss";
@import "node_modules/@getscope/npm-webfont-exo2/src/scss/_all-italic.scss";
```
