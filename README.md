# drop-media

Файлы для карточек товара магазина: видео и крупные картинки, которые
не помещаются в KV (там потолок 25 МБ на файл).

## Как добавить файл

```bash
gh release upload media путь/к/файлу.mp4 --repo meloff/drop-media --clobber
```

Ссылка для вставки в админку:

```
https://github.com/meloff/drop-media/releases/download/media/файл.mp4
```

Файлы до 50 МБ можно класть прямо в репозиторий — тогда их раздаёт jsDelivr,
это заметно быстрее:

```
https://cdn.jsdelivr.net/gh/meloff/drop-media@main/файл.mp4
```
