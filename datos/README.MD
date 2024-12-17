# Datos

Por razones de seguridad y privacidad, los datos etiquetados no pueden ser compartidos. En esta carpeta se encuentran aquellos recursos auxiliares para la identificación de consultas de SSyR y PCD.

- *cie-10_clasificados_pcd.csv*: A partir de los códigos CIE-10 presentes en la base de datos (12.707), se tomaron sólo aquellos utilizados (5.588), es decir asociados a una consulta y se los clasificó según si figuran en las Normativas para la Certificación de Personas con Discapacidad (648/15, 1019/15, 639/15, 82/15 y 500/15), identificándose 613. El archivo incluye las variables:
  - ID: identificador en la base
  - codigo-CIE10: código CIE-10
  - descripcion: descripción del código
  - sinonimos: sinónimo en la Clasificación Estadística de Problemas de Salud en Atención Primaria (CEPS-AP) 
  - sexo: sexo al que aplica el código (F: femenino / M: masculino / I: indistinto)
  - anexo: con qué anexo se relaciona (Visceral / Motor / Mental / Visual / Auditivo)

- *terminos_de_búsqueda*: Términos de búsqueda elegidos para cada una de las áreas temáticas (PCD y SSyR). Para su uso en la búsqueda en textos de los registros electrónicos se considerarán sus combinaciones, uso de acentos (por ej. serolog.a recupera serología y serologia), derivados (sex+, recupera sexo, sexualidad, sexy), y se ignorará el uso de mayúsculas (por ej. se recuperará VIH y vih). os términos se agrupan según factores en común para facilitar su manipulación, pero estas agrupaciones no representan una tipificación real. El archivo incluye las variables:
  - termino: palabra a ser buscada
  - subcategoria: agrupación dentro de una dada área temática (Derechos
  - categoria: área temática (ssyr / pcd)





