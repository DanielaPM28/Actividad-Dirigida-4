
# Viajes nacionales en Colombia
###### Por: Daniela Pinto M

Según el Centro de Información Turística de Colombia (CITUR), al segundo semestre de 2021 se registra la llegada de 10.372.490 viajeros nacionales, siendo Cundinamarca (Bogotá D.C.), Antioquia y Valle del Cauca los departamentos con más visitantes.

La pandemia también afectó el flujo de viajeros al interior del país. En 2019 se presentaron 26.260.928 viajeros y en 2020, la cifra disminuyó a 8.891.059. En solo seis meses de 2021, los colombianos viajaron más que el año pasado.

<iframe title="Viajes nacionales en Colombia" aria-label="Gráfico de columnas" id="datawrapper-chart-Qx1AG" src="https://datawrapper.dwcdn.net/Qx1AG/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();

</script>

**Realización**

Para la realización de la pieza de visualización desde cero, escogí el tema de viajes nacionales aéreos en Colombia para conocer el comportamiento del turismo doméstico por departamentos en el país. Al ingresar al Centro de Información Turística de Colombia [(CITUR)](https://www.citur.gov.co/estadisticas/df_pax_aereos_nacionales/all/15#gsc.tab=0) encontré los datos y los descargué en un archivo de Excel.

Luego, ingresé a Open Refine en donde nombré el archivo y lo etiqueté con las palabras Vuelos, Turismo y Colombia. De igual forma, se editaron los nombres de las columnas y se transformaron en números para los años y textos. También encontré que los datos del departamento de Boyacá están en cero, lo anterior al no tener aeropuerto activo abierto al público. Así que procedí a eliminar la fila. Para tener una mejor graficación, solo dejé los datos de 2017 al primer semestre de 2021.

En el análisis encontré que al aplicar la faceta numérica los únicos departamentos entre 1.000.000 y 3.000.000 de viajes fueron Antioquia y Bogotá D.C. (Se toma a Bogotá en representación del departamento de Cundinamarca por ser la capital de Colombia). Por su parte, de 500.000 a 3.000.000 viajes se realizaron en Antioquia, Bogotá, Bolívar, Magdalena, Valle del Cauca y Archipiélago de San Andrés, Providencia y Santa Catalina.

Para la creación del gráfico en [Datawrapper]([https://datawrapper.dwcdn.net/Qx1AG/1/](https://datawrapper.dwcdn.net/Qx1AG/1/)) escogí uno de columnas en el que el lector puede escoger el año en el que desea ver los datos. En este, cada vez que se cambia de año automáticamente se cambia el orden de departamentos de mayor a menor viajes. También debe pasar el cursor sobre las barras para ver la cantidad de viajes. El lector puede descargar los datos directamente del CITUR.
