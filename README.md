# S-Mitler

gulp watch

Как исправить ошибку "ReferenceError: Primordials is not defined"

**1.** Создать `npm-shrinkwrap.json` файл со следующим содержимым:

`{
  "dependencies": {
    "graceful-fs": {
        "version": "4.2.2"
     }
  }
}`

**2.** Запустить `npm install` и не волнуйтесь, он обновится, добавив в `npm-shrinkwrap.json` кучу контента