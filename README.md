# Ejercicios Iniciación sobre el plugin de jQuery datatables.


1. Actualiza el ejercicio1.html para que la tabla se vea mediante el plugin de jquery.  Comprueba que mediante el plugin la tabla dispone de: paginación, filtrado y ordenamiento por columnas.
Pasos orientativos:
- Como en cualquier otro plugin jquery, cargar jquery antes que el plugin
- Cargar el plugin ( jquery.dataTables.js).
- Asociar el plugin de jquery a la tabla en cuestión, según la documentación de datatables.

2. Personaliza la tabla del ejercicio2, eliminando el filtrado y la paginación, mediante el uso de variables en la inicialización del objeto datatables.

3. Personaliza la tabla del ejercicicio 3 para que los datos aparezcan ordenados por las dos últimas columnas: CSS grade descendente y Engine Version ascendente.

4. Personaliza la tabla del ejercicio4 para que cumpla las siguientes condiciones:
Los datos aparecen ordenados por la primera columna de forma alfabética
Las columnas Platform y Engine version deben permanecer invisibles, sin embargo se pueden hacer búsquedas (filtrados) por la primera de ellas. 
No se pueden ordenar los datos por la última columna (CSS grade).

5. Si cambiamos la paginación del ejercicio5, o ponemos un filtro y vamos hacía atrás y hacía adelante con el historial del navegador se debería mantener el filtro o la paginación. Comprueba si es así y en caso negativo, arréglalo.

6. Cambia los mensajes del ejercicio anterior a español.

7. Cambia el aspecto del datatables mediante themeroller. ¡Ojo, deberás añadir los css correspondientes!:
demo_table_jui.css (jui=jquery user interface), en vez de demo_table.css)
y jquery-ui-1.8.4.custom.css
8. Crea tu propio theme mediante themeroller e integralo en datatables. Página de referencia: http://jqueryui.com/themeroller/
