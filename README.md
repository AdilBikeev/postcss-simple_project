# Запускааем команду
`npm install live-server node-sass postcss-cli postcss-custom-properties`

- live-server нужен для автообновлений старницы по мере изменений в проекте
- node-sass нужен для демонтсрации как работать с sass
- postcss-cli (https://github.com/postcss/postcss-cli) - утилита для работы с postcss через CMD
Например может параллелньо компилировать файл с PostCss в обычный .css

- `npx live-server` для запуска с автообновлениями 

- `npx node-sass index.scss --watch index.css` преобразуте файл .scss
в обычный css параллельно с отлсеживанием изменений

- `npx postcss index.css --use postcss-custom-properties --no map --watch --output post.css`
Делает тоже саммое, что и предыдущая команда
