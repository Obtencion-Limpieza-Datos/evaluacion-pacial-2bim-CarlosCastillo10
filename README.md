
# evaluacion-final

1. Hacer scrapy de la página https://es.wikipedia.org/wiki/Prefectos_provinciales_del_Ecuador

Generar un archivo con los siguientes datos:

Nombre|Provincia|Partido|AnioInicio|AnioFin

2.- Ingresar a cada enlace de la columna predecesor

Ejm.
https://es.wikipedia.org/wiki/Anexo:Prefectos_de_Azuay

y agregar datos al primer archivo

Nombre|Provincia|Partido|AnioInicio|AnioFin

3.- Leer el csv final generado y presentar los prefectos en base a la provincia.
- Usar un widget de ipython

4.- Subir todo al repositorio

----------------------------------------------------------------------------------------------------
AUTORES:
	Carlos Castillo
	Enrique Cueva

PROCEDIMIENTO:

IMPORTANTE:
	Entrar a la carpeta con el nombre 'evaluacion_corregida' y seguir los siguientes pasos

	1. Ejecturar: 
		scrapy crawl datos_prefectos
	2. Ejecutar:
		scrapy crawl datos_prefectos1
	3. Ejectutar:
		scrapy crwal datos_prefectos2
	
	4. Entrar a la carpeta 'notebooks' y levantar jupyter y ejecutar el notebook'evaluacion.ipynb'

NOTA:
	No se adjuntan las datas resultantes para que al momento que realice los pasos 1, 2 y 3 se generen.



