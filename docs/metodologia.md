# Metodología

## 1. Selección de genes y variantes

El proyecto se desarrolló de manera colaborativa, asignando a cada integrante un gen humano para su documentación.

Cada participante consultó la base de datos ClinVar del NCBI y seleccionó cinco variantes genéticas asociadas a su gen. La selección tuvo una finalidad educativa y no respondió a un criterio uniforme de patogenicidad, frecuencia poblacional o relevancia clínica.

## 2. Recopilación y organización de datos

Para cada variante se registró la nomenclatura HGVS, el identificador de ClinVar, la clasificación clínica, el tipo de clasificación, el estado de revisión y la condición asociada, según la información disponible.

Los resultados se organizaron en archivos CSV dentro de la carpeta `datos/`. Paralelamente, cada gen se documentó en un archivo Markdown dentro de `genes/`, incluyendo su función biológica, importancia biomédica, variantes seleccionadas, observaciones y referencias.

## 3. Trabajo colaborativo

Se utilizó GitHub para organizar el repositorio y gestionar las contribuciones individuales.

Los integrantes trabajaron mediante ramas, registraron sus cambios con commits y utilizaron pull requests para proponer la incorporación de sus aportes a la rama principal (`main`), requiriendo la revisión y aprobación de al menos un compañero del grupo antes de su integración definitiva en el repositorio. 

## 4. Alcance y limitaciones

El catálogo tiene carácter académico y educativo. Las variantes seleccionadas no constituyen una muestra representativa de todas las variantes registradas para cada gen.

Las clasificaciones clínicas corresponden a la información disponible en ClinVar en las fechas de consulta indicadas en los documentos individuales y pueden modificarse con nuevas evidencias.
