# PDF OCR fácil — PaddleOCR + Google Colab

Proyecto pensado para compañeros de clase que no necesitan saber programar.

## Archivos

- `index.html`: página para GitHub Pages.
- `PaddleOCR_PDF.ipynb`: notebook que convierte PDF → PDF con OCR buscable.

## Cómo publicarlo

1. Subí `index.html` y `PaddleOCR_PDF.ipynb` a la raíz de un repositorio público.
2. La rama debe llamarse `main`.
3. En GitHub: **Settings → Pages → Deploy from a branch → main / root**.
4. Abrí tu GitHub Pages.

El `index.html` detecta automáticamente tu usuario y el nombre del repositorio,
así que no hace falta editar el enlace a Colab.

## Qué recibe el usuario

`apunte.pdf` → `apunte_OCR.pdf`

Se conservan las páginas del PDF y se agrega una capa de texto invisible,
seleccionable y buscable.
