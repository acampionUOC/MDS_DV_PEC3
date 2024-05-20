# dataset para proyecto visualización de datos
## Descripción
Este proyecto permite generar el conjunto de datos para generar la visualización tipo Dashboard propuesta como solución a la PEC3 de la asignatura Visualización de Datos correspondiente al plan de estudios del Máster de Ciencia de Datos en la Universitat Oberta de Catalunya.
<br><br>
La visualización propuesta es de tipo Dashboard para poder hacer un análisis de los resultados electorales en las elecciones autonómicas en Cataluña el 14 de Febrero de 2021 y del 12 de Mayo de 2024.<br>
Mediante el desarrollo de este proyecto se facilita un objeto visual que permite realizar los siguientes análisis:
- resultados electorales y tono político por Territorio.
- posicionamiento ideológico de fuerzas políticas con representación y número de Diputados.
- posicionamiento ideológico diferentes Territorios.
- cambio en el posicionamiento ideológico entre 2021 y 2024 entre los diferentes Territorios.

<br><br>
El proyecto contiene los siguientes ficheros:
- input\A2021-Columnes-MU.csv se trata de un fichero con los resultados electorales de las elecciones autonómicas en Cataluña el 14 de Febrero de 2021. El fichero se ha obtenido de la siguiente referencia:
<br>  https://eleccions.gencat.cat/es/resultats-i-eleccions-anteriors/resultats-electorals/#/dades?tipusProces=A&proces=A20211#dades
<br> 
- input\Aepc_2024.csv se trata de un fichero con los resultados electoras de las elecciones autonómicas en Cataluña el 12 de Mayo de 2024. El fichero se ha obtenido de la siguiente referencia:
<br>  https://resultados.eleccionsparlament.cat/es/descargas (Descargado en fecha 13 de Mayo 2024 con un escrutionio al 99.48%)

La Generalitat de Cataluña permite la reutilización de los contenidos y de los datos para todo el mundo y sin limitaciones temporales ni restricciones, en los términos establecidos por la Licencia abierta de uso de información – Cataluña o por el equivalente instrumento legal CC0 de Creative Commons.
<br>
- input\Municipios.csv: fichero con los coordenadas geográficas de todos los municipios de España. Fuente:
<br> https://centrodedescargas.cnig.es/CentroDescargas/catalogo.do?Serie=CAANE
<br>

Son datos publicados por el Ministerio de Transportes y Movilidad Sostenible de forma pública. El usuario no podrá usar el presente sitio web con ninguna finalidad o propósito que sea ilegal o esté prohibido, y no se permite cualquier actuación en perjuicio del IGN, del CNIG o terceros. El usuario debe acceder a los sitios web y usar sus contenidos de forma correcta y lícita y, en particular, se compromete a hacer uso de las utilidades y servicios ofrecidos a través del sitio web de conformidad con la legalidad vigente en cada momento.
<br>
- input\gp_cat.csv se trata de un fichero generado manualmente con resultados electorales de los diferentes grupos políticos de las webs mencionadas anteriormente y donde se ha añadido información consultada manualmente en Wikipedia sobre la posición ideológica de cada partido político con representación de diputados en las elecciones de 2021 o 2024.

<br>

La visualización resultante generada en Tableau Public se puede encontrar en el siguiente link:
https://public.tableau.com/app/profile/alvaro.campion/viz/PEC3_acampion/Dashboard3

## Autores
El autor del proyecto es:
- Alvaro Campion Mezquiriz (acampion@uoc.edu)

## Instalación
Clonar el repositorio para su instalación <br>

'''
git clone https://github.com/acampionUOC/MDS_DV_PEC3.git
'''

# Ejecución
El proyecto se ha desarrollado en el notebook notebooks\pec3_data.ipynb
<br>
