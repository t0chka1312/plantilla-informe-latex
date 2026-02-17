# plantilla-informe-latex
Plantilla para informes de auditorías de pentesting en LaTeX.
---------
Comandos a ejecutar:
``` bash
mkdir plantilla
git clone https://github.com/t0chka1312/plantilla-informe-latex
cd plantilla-informe-latex
latexmk -pdf plantilla.tex -pvc -> Para compilar y ver cambios

En caso de error:
latexmk -C
latexmk -pdf plantilla.tex -> Después con la opción -pvc
```

También está el comprimido con la estructura completa, en caso de usar el comprimido:

``` bash
mkdir plantilla
mv plantilla_informe_LaTeX.zip plantilla
cd plantilla
unzip plantilla_informe_LaTeX.zip
```
El archivo PDF es la muestra de cómo queda.
