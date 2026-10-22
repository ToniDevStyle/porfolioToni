# CV

`cv-es.html` es la fuente del CV. El PDF que enlaza la web está en `public/cv/Toni-Vieira-Rubio-CV.pdf`.

Para regenerarlo después de cambiar el HTML (con Google Chrome instalado en el Mac):

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --no-pdf-header-footer \
  --print-to-pdf=public/cv/Toni-Vieira-Rubio-CV.pdf cv/cv-es.html
```
