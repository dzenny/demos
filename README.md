Demos
===============


## Установка

Должны быть:
* A pre-release version of Quarto (version 1.2.x). You can download it [here](https://quarto.org/docs/download/).
* Python 3.8 or above.
* The [`shinylive`](https://github.com/rstudio/py-shinylive) Python package, which can be installed with:
    ```
    pip install shinylive
    ```

Далее 

1. Создать quarto проект, например, `demos`:

```bash
quarto create-project demos --type website
```

2. Перейти в созданную папку `demos`, например, так:
```bash
cd demos
```


3. Установить для `shinylive-quarto` расширение:
```bash
quarto install extension quarto-ext/shinylive
```

This will install the extension under the `_extensions/` subdirectory.

Для использования в git, нужно включить эту поддиректорию в список отслеживаемых.

