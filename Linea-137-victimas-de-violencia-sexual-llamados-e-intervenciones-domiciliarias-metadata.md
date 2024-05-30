Línea 137 - víctimas de violencia sexual - llamados e intervenciones domiciliarias
--------------------------------------------------------------------------------------------

Este conjunto de datos contiene los llamados atendidos por las y los profesionales de la Línea 137, de alcance nacional, sobre casos de violencia sexual y las intervenciones domiciliarias efectuadas a partir de dichos llamados. Los llamados pueden ingresar por dos vías: 137 y 0800-222-1717 (ambas de alcance nacional) y también forman parte de este conjunto de datos, los mails y formularios web que ingresan al Programa denunciando situaciones de pornografía infantil, grooming y explotación sexual comercial de niñas, niños y adolescentes. Se cuenta con datos de llamados desde noviembre de 2016, año en que se lanzó la Campaña Nacional "Abuso Sexual Infantil: Hablar es empezar a prevenir", y de intervenciones domiciliarias desde enero de 2018. Link al formulario de denuncia: https://www.argentina.gob.ar/violencia-familiar-y-sexual

http://datos.jus.gob.ar/dataset/linea-137-victimas-de-violencia-sexual

Características
---------------

-   **Fecha de Primera** **Publicación:** 07/02/2018

-   **Tags o Etiquetas:** 137, 0800-222-1717, abusos, adolescentes, intervención domiciliaria, línea 0800, niñas, niños, sexuales, violencias, víctimas

-   **Organización:** Ministerio de Justicia. Subsecretaría de Acceso a la Justicia. Programa Las Víctimas Contra Las Violencias

-   **Autor:** Ministerio de Justicia. Subsecretaría de Acceso a la Justicia. Programa Las Víctimas Contra Las Violencias

-   **Responsable:** Ministerio de Justicia. Subsecretaría de Acceso a la Justicia. Programa Las Víctimas Contra Las Violencias

-   **Grupo:** Acceso a Justicia

-   **Frecuencia de Actualización:** Trimestralmente

Recursos disponibles
--------------------

### Llamados atendidos sobre abuso sexual - Línea 137 - AAAAMM

-   **Nombre del archivo:** llamados-atendidos-abuso-sexual-AAAA.csv

-   **Descripción del contenido:** Detalle de los llamados de todo el país atendidos por las y los profesionales de la Línea 137, de alcance nacional, sobre casos de violencia sexual correspondientes al período comprendido entre enero y el mes del año indicado en el título.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** llamados atendidos desde noviembre de 2016 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **caso_id (int):** código que permite identificar el caso (este campo es publicado a partir del 4to. trimestre de 2019)

-   **llamado_fecha_hora (date):** fecha y hora en la que se realiza el llamado a la Línea 137/0800-222-1717

-   **llamado_region (string):** región desde la que se realiza el llamado a la Línea 137/0800-222-1717. Las regiones son
    -   NOA: Tucumán, Salta, Jujuy, La Rioja, Catamarca, Santiago del Estero
    -   NEA: Misiones, Corrientes, Formosa, Chaco
    -   CUYO: Mendoza, San Juan, San Luis
    -   PAMPEANA: Córdoba, Santa Fe, Entre Ríos, La Pampa
    -   METROPOLITANA: Ciudad de Buenos Aires, Provincia de Buenos Aires
    -   PATAGONIA: Tierra del Fuego, Santa Cruz, Chubut, Río Negro, Neuquén

-   **llamante_edad (int):** edad de la persona que llama a la Línea 137/0800-222-1717

-   **llamante_genero (string):** género de la persona que llama a la Línea 137/0800-222-1717. Toma los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   NS/NC: No sabe / No contesta

-   **llamante_vinculo (string):** describe el vínculo que tiene la persona que llama a la Línea 137/0800-222-1717 con la víctima

-   **caso_judicializado (string):** describe si el caso se encuentra judicializado. Toma los valores:

    -   SI

    -   NO

    -   NS/NC: No sabe / No contesta

-   **hecho_lugar (string):** describe el lugar donde se produjo el hecho

-   **victima_a_resguardo (string):** describe si la víctima se encuentra a resguardo. Toma los valores

    -   SI

    -   NO

-   **victima_edad (int):** describe la edad de la víctima

-   **victima_genero (string):** describe el género de la víctima. Toma los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   NS/NC: No sabe / No contesta

-   **victima_nacionalidad (string):** describe la nacionalidad de la víctima

-   **victima_vinculo_agresor(string):** describe el vínculo que tiene la víctima con el agresor (¿Qué es el agresor de la víctima?)

-   **victima_discapacidad (string):** describe si la víctima posee algún tipo de discapacidad. Toma los valores SI/NO

-   **victima_convive_agresor: (string):** describe si la víctima convive con el agresor. Toma los valores SI/NO

-   **vs_violacion_via_vaginal (string):** vs - violencia sexual. Describe violación vía vaginal. Toma los valores SI/NO

-   **vs_violacion_via_anal (string):** vs - violencia sexual. Describe violación vía anal. Toma los valores SI/NO

-   **vs_violacion_via_oral (string):** vs - violencia sexual. Describe violación vía oral. Toma los valores SI/NO

-   **vs_tentativa_violacion (string):** vs - violencia sexual. Describe tentativa de violación. Toma los valores SI/NO

-   **vs_tocamiento_sexual (string):** vs - violencia sexual. Describe tocamiento sexual. Toma los valores SI/NO

-   **vs_intento_tocamiento (string):** vs - violencia sexual. Describe intento de tocamiento.  Toma los valores SI/NO

-   **vs_intento_violacion_tercera_persona (string):** vs - violencia sexual. Describe intento de violación por tercera persona. Toma los valores SI/NO

-   **vs_violencia_digital (string):** vs - violencia sexual. Describe violencia digital. Toma los valores SI/NO (hasta el año 2022 nombre de campo: fv_grooming)

-   **vs_exhibicionismo (string):** vs - violencia sexual. Describe exhibicionismo. Toma los valores SI/NO

-   **vs_amenazas_verbales_contenido_sexual (string):** vs - violencia sexual. Describe amenazas verbales con contenido sexual. Toma los valores SI/NO

-   **vs_explotacion_sexual (string):** vs - violencia sexual. Describe explotación sexual. Toma los valores valores SI/NO

-   **vs_explotacion_sexual_comercial (string):** vs - violencia sexual. Describe explotación sexual comercial. Toma los valores SI/NO

-   **vs_explotacion_sexual_viajes_turismo (string):** vs - violencia sexual. Describe explotación sexual en viajes de turismo. Toma los valores SI/NO

-   **vs_sospecha_trata_personas_fines_sexuales (string):** vs - violencia sexual. Describe sospecha de trata de personas con fines sexuales. Toma los valores SI/NO

-   **vs_existencia_facilitador_corrupcion_nnya (string):** vs - violencia sexual. Describe existencia de un facilitador a la corrupción de niños, niñas y adolescentes. Toma los valores SI/NO

-   **vs_obligacion_sacarse_fotos_pornograficas (string):** vs - violencia sexual. Describe si la víctima fue obligada a sacarse fotos pornográficas. Toma los valores SI/NO

-   **vs_eyaculacion_partes_cuerpo (string):** vs - violencia sexual. Describe la eyaculación en partes del cuerpo. Toma los valores SI/NO

-   **vs_acoso_sexual (string):** vs - violencia sexual. Describe acoso sexual. Toma los valores SI/NO

-   **vs_iniciacion_sexual_forzada_inducida (string):** vs - violencia sexual. Describe iniciación sexual forzada o inducida. Toma los valores SI/NO

-   **vs_otra_forma_violencia_sexual (string):** vs - violencia sexual. Describe otra forma de violencia sexual. Toma los valores SI/NO

-   **vs_no_sabe_no_contesta (string):** vs - violencia sexual. Describe de violencia sexual que se desconoce o que NO hace referencia a los campos mencionados anteriormente. Toma los valores SI/NO

-   **ofv_sentimiento_amenaza (string):** ofv - otras formas de violencia. Describe sentimiento de amenaza. Toma los valores SI/NO

-   **ofv_amenazas_explicitas (string):** ofv - otras formas de violencia. Describe amenazas explícitas. Toma los valores SI/NO

-   **ofv_violencia_fisica (string):** ofv - otras formas de violencia. Describe violencia física. Toma los valores SI/NO

-   **ofv_intento_ahorcar (string):** ofv - otras formas de violencia. Describe si trataron de ahorcar a la víctima. Toma los valores SI/NO

-   **ofv_intento_quemar (string):** ofv - otras formas de violencia. Describe si trataron de quemar a la víctima. Toma los valores SI/NO

-   **ofv_intento_ahogar (string):** ofv - otras formas de violencia. Describe si trataron de ahogar a la víctima. Toma los valores SI/NO

-   **ofv_amenaza_muerte (string):** ofv - otras formas de violencia. Describe si la víctima recibió amenazas de muerte. Toma los valores SI/NO

-   **ofv_uso_sustancias_psicoactivas (string):** ofv - otras formas de violencia. Describe si la víctima recibió sustancias psicoactivas. Toma los valores SI/NO

-   **ofv_intento_privacion_libertad (string):** ofv - otras formas de violencia. Describe intento de privación de libertad. Toma los valores SI/NO

-   **ofv_privacion_libertad (string):** ofv - otras formas de violencia. Describe privación de libertad. Toma los valores SI/NO

-   **ofv_uso_arma_blanca (string):** ofv - otras formas de violencia. Describe uso de arma blanca. Toma los valores SI/NO

-   **ofv_uso_arma_fuego (string):** ofv - otras formas de violencia. Describe uso de arma de fuego. Toma los valores SI/NO

-   **ofv_enganio_seduccion (string):** ofv - otras formas de violencia. Describe engaño o seducción. Toma los valores SI/NO

-   **ofv_intento_matar (string):** ofv - otras formas de violencia. Describe intento de asesinato. Toma los valores SI/NO

-   **ofv_uso_animal_victimizar (string):** ofv - otras formas de violencia. Describe la utilización de un animal para victimizar. Toma los valores SI/NO

-   **ofv_extorsion_redes_sociales (string):** ofv - otras formas de violencia. Describe extorsión redes sociales. Toma los valores SI/NO (hasta el año 2022 nombre de campo: ofv_grooming)

-   **ofv_otra_forma_violencia (string):** ofv - otras formas de violencia. Describe otra forma de violencia. Toma los valores SI/NO

-   **ofv_no_sabe_no_contesta (string):** vs - violencia sexual. Describe de otras formas de violencias que se desconocen o que no hacen referencia a los campos mencionados anteriormente. Toma los valores SI/NO


### Intervenciones domiciliarias por casos de abuso sexual - Línea 137 - AAAAMM

-   **Nombre del archivo:** intervenciones-domiciliarias-abuso-sexual-AAAAMM.csv

-   **Descripción del contenido:** detalle de Intervenciones domiciliarias por casos de violencia sexual efectuadas en CABA por el equipo móvil, luego de los llamados recibidos en la Línea 137/0800-222-1717 (ambas de alcance nacional). La unidad de análisis en este recurso es la víctima (puede haber más de una víctima/fila por intervención).

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** intervenciones realizadas desde enero de 2018 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **caso_id (int):** código que permite identificar el caso (este campo es publicado a partir del 1er. trimestre de 2020)

-   **intervención_fecha_hora (string):** fecha y hora en la que se realiza la intervención

-   **victima_edad (entero):** edad de víctima

-   **victima_convive_agresor: (string):** describe si la víctima convive con el agresor. Toma los valores:

    -   SI

    -   NO
    
-   **victima_nacionalidad (string):** nacionalidad de la víctima

-   **victima_genero (string):** género de la víctima. Toma los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   NS/NC: No sabe / No contesta

-   **victima_discapacidad (string):** describe si la víctima posee algún tipo de discapacidad. Toma los valores:

    -   SI

    -   NO

-   **victima_vinculo_agresor (string):** describe el vínculo que tiene la víctima con el agresor (¿Qué es el agresor de la víctima?)

-   **vs_violacion_via_vaginal (string):** vs - violencia sexual. Describe violación vía vaginal. Toma los valores SI/NO

-   **vs_violacion_via_anal (string):** vs - violencia sexual. Describe violación vía anal. Toma los valores SI/NO

-   **vs_violacion_via_oral (string):** vs - violencia sexual. Describe violación vía oral. Toma los valores SI/NO

-   **vs_tentativa_violacion (string):** vs - violencia sexual. Describe tentativa de violación. Toma los valores SI/NO

-   **vs_tocamiento_sexual (string):** vs - violencia sexual. Describe tocamiento sexual. Toma los valores SI/NO

-   **vs_intento_tocamiento (string):** vs - violencia sexual. Describe intento de tocamiento. Toma los valores SI/NO

-   **vs_intento_violacion_tercera_persona (string):** vs - violencia sexual. Describe intento de violación por tercera persona. Toma los valores SI/NO

-   **vs_grooming (string):** vs - violencia sexual. Describe Grooming. Toma los valores SI/NO

-   **vs_exhibicionismo (string):** vs - violencia sexual. Describe exhibicionismo. Toma los valores SI/NO

-   **vs_amenazas_verbales_contenido_sexual (string):** vs - violencia sexual. Describe amenazas verbales con contenido sexual. Toma los valores SI/NO

-   **vs_explotacion_sexual (string):** vs - violencia sexual. Describe explotación sexual. Toma los valores SI/NO

-   **vs_explotacion_sexual_comercial (string):** vs - violencia sexual. Describe explotación sexual comercial. Toma los valores SI/NO

-   **vs_explotacion_sexual_viajes_turismo (string):** vs - violencia sexual. Describe explotación sexual en viajes de turismo. Toma los valores SI/NO

-   **vs_sospecha_trata_personas_fines_sexuales (string):** vs - violencia sexual. Describe sospecha de trata de personas con fines sexuales. Toma los valores SI/NO

-   **vs_existencia_facilitador_corrupcion_nnya (string):** vs - violencia sexual. Describe existencia de un facilitador a la corrupción de niños, niñas y adolescentes. Toma los valores SI/NO

-   **vs_obligacion_sacarse_fotos_pornograficas (string):** vs - violencia sexual. Describe si la víctima fue obligada a sacarse fotos pornográficas. Toma los valores SI/NO

-   **vs_eyaculacion_partes_cuerpo (string):** vs - violencia sexual. Describe la eyaculación en partes del cuerpo. Toma los valores SI/NO

-   **vs_acoso_sexual (string):** vs - violencia sexual. Describe acoso sexual. Toma los valores SI/NO

-   **vs_iniciacion_sexual_forzada_inducida (string):** vs - violencia sexual. Describe iniciación sexual forzada o inducida. Toma los valores SI/NO

-   **vs_otra_forma_violencia_sexual (string):** vs - violencia sexual. Describe otra forma de violencia sexual. Toma los valores SI/NO

-   **vs_no_sabe_no_contesta (string):** vs - violencia sexual. Describe de violencia sexual que se desconoce o que no hace referencia a los campos mencionados anteriormente. Toma los valores SI/NO

-   **ofv_sentimiento_amenaza (string):** ofv - otras formas de violencia. Describe sentimiento de amenaza. Toma los valores SI/NO

-   **ofv_amenaza_explicita (string):** ofv - otras formas de violencia. Describe amenazas explícitas. Toma los valores SI/NO

-   **ofv_violencia_fisica (string):** ofv - otras formas de violencia. Describe violencia física. Toma los valores SI/NO

-   **ofv_intento_ahorcar (string):** ofv - otras formas de violencia. Describe si trataron de ahorcar a la víctima. Toma los valores SI/NO

-   **ofv_intento_quemar (string):** ofv - otras formas de violencia. Describe si trataron de quemar a la víctima. Toma los valores SI/NO

-   **ofv_intento_ahogar (string):** ofv - otras formas de violencia. Describe si trataron de ahogar a la víctima. Toma los valores SI/NO

-   **ofv_amenaza_muerte (string):** ofv - otras formas de violencia. Describe si la víctima recibió amenazas de muerte. Toma los valores SI/NO

-   **ofv_uso_sustancias_psicoactivas (string):** ofv - otras formas de violencia. Describe si la víctima recibió sustancias psicoactivas. Toma los valores SI/NO

-   **ofv_intento_privacion_libertad (string):** ofv - otras formas de violencia. Describe intento de privación de libertad. Toma los valores SI/NO

-   **ofv_privacion_libertad (string):** ofv - otras formas de violencia. Describe privación de libertad. Toma los valores SI/NO

-   **ofv_uso_arma_blanca (string):** ofv - otras formas de violencia. Describe uso de arma blanca. Toma los valores SI/NO

-   **ofv_uso_arma_fuego (string):** ofv - otras formas de violencia. Describe uso de arma de fuego. Toma los valores SI/NO

-   **ofv_enganio_seduccion (string):** ofv - otras formas de violencia. Describe engaño o seducción. Toma los valores SI/NO

-   **ofv_intento_matar (string):** ofv - otras formas de violencia. Describe intento de asesinato. Toma los valores SI/NO

-   **ofv_uso_animal_victimizar (string):** ofv - otras formas de violencia. Describe la utilización de un animal para victimizar. Toma los valores SI/NO

-   **ofv_grooming (string):** ofv - otras formas de violencia. Describe Grooming. Toma los valores SI/NO

-   **ofv_otra_forma_violencia (string):** ofv - otras formas de violencia. Describe otra forma de violencia. Toma los valores SI/NO

-   **ofv_no_sabe_no_contesta (string):** ofv - otras formas de violencia. Describe de otras formas de violencias que se desconocen o que no hacen referencia a los campos mencionados anteriormente. Toma los valores SI/NO

### Llamados atendidos sobre abuso sexual - Línea 137 - AAAA trimestre 9

-   **Nombre del archivo:** llamados-atendidos-abuso-sexual-AAAA-trimestre-9.csv

-   **Descripción del contenido:** detalle de los llamados de todo el país atendidos por las y los profesionales de la Línea 137/0800-222-1717 (ambas de alcance nacional), sobre casos de violencia sexual. Trimestre 9: Toma valores 1; 2; 3 y 4 (cada número hace referencia al trimestre del año indicado).

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** llamados atendidos en la Línea 137/0800-222-1717 desde noviembre de 2016 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **caso_id (int):** código que permite identificar el caso (este campo es publicado a partir del 4to. trimestre de 2019)

-   **llamado_fecha_hora (date):** fecha y hora en la que se realiza el llamado a la Línea 137/0800-222-1717

-   **llamado_provincia (string):** provincia desde la que se realiza el llamado a la Línea 137/0800-222-1717

-   **llamante_edad (int):** edad de la persona que llama a la Línea 137/0800-222-1717

-   **llamante_genero (string):** género de la persona que llama a la Línea 137/0800-222-1717. Toma los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   NS/NC: No sabe / No contesta

-   **llamante_vinculo (string):** describe el vínculo que tiene la persona que llama a la Línea 137/0800-222-1717 con la víctima

-   **caso_judicializado (string):** describe si el caso se encuentra judicializado. Toma los valores:

    -   SI

    -   NO

    -   NS/NC: No sabe / No contesta

-   **hecho_lugar (string):** describe el lugar donde se produjo el hecho

-   **victima_a_resguardo (string):** describe si la víctima se encuentra a resguardo. Toma los valores

    -   SI

    -   NO

-   **victima_edad (int):** describe la edad de la víctima

-   **victima_genero (string):** describe el género de la víctima. Toma los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   NS/NC: No sabe / No contesta

-   **victima_nacionalidad (string):** describe la nacionalidad de la víctima

-   **victima_vinculo_agresor(string):** describe el vínculo que tiene la víctima con el agresor (¿Qué es el agresor de la víctima?)

-   **victima_discapacidad (string):** describe si la víctima posee algún tipo de discapacidad. Toma los valores SI/NO

-   **victima_convive_agresor: (string):** describe si la víctima convive con el agresor. Toma los valores SI/NO

-   **vs_violacion_via_vaginal (string):** vs - violencia sexual. Describe violación vía vaginal. Toma los valores SI/NO

-   **vs_violacion_via_anal (string):** vs - violencia sexual. Describe violación vía anal. Toma los valores SI/NO

-   **vs_violacion_via_oral (string):** vs - violencia sexual. Describe violación vía oral. Toma los valores SI/NO

-   **vs_tentativa_violacion (string):** vs - violencia sexual. Describe tentativa de violación. Toma los valores SI/NO

-   **vs_tocamiento_sexual (string):** vs - violencia sexual. Describe tocamiento sexual. Toma los valores SI/NO

-   **vs_intento_tocamiento (string):** vs - violencia sexual. Describe intento de tocamiento.  Toma los valores SI/NO

-   **vs_intento_violacion_tercera_persona (string):** vs - violencia sexual. Describe intento de violación por tercera persona. Toma los valores SI/NO

-   **vs_grooming (string):** vs - violencia sexual. Describe Grooming. Toma los valores SI/NO

-   **vs_exhibicionismo (string):** vs - violencia sexual. Describe exhibicionismo. Toma los valores SI/NO

-   **vs_amenazas_verbales_contenido_sexual (string):** vs - violencia sexual. Describe amenazas verbales con contenido sexual. Toma los valores SI/NO

-   **vs_explotacion_sexual (string):** vs - violencia sexual. Describe explotación sexual. Toma los valores valores SI/NO

-   **vs_explotacion_sexual_comercial (string):** vs - violencia sexual. Describe explotación sexual comercial. Toma los valores SI/NO

-   **vs_explotacion_sexual_viajes_turismo (string):** vs - violencia sexual. Describe explotación sexual en viajes de turismo. Toma los valores SI/NO

-   **vs_sospecha_trata_personas_fines_sexuales (string):** vs - violencia sexual. Describe sospecha de trata de personas con fines sexuales. Toma los valores SI/NO

-   **vs_existencia_facilitador_corrupcion_nnya (string):** vs - violencia sexual. Describe existencia de un facilitador a la corrupción de niños, niñas y adolescentes. Toma los valores SI/NO

-   **vs_obligacion_sacarse_fotos_pornograficas (string):** vs - violencia sexual. Describe si la víctima fue obligada a sacarse fotos pornográficas. Toma los valores SI/NO

-   **vs_eyaculacion_partes_cuerpo (string):** vs - violencia sexual. Describe la eyaculación en partes del cuerpo. Toma los valores SI/NO

-   **vs_acoso_sexual (string):** vs - violencia sexual. Describe acoso sexual. Toma los valores SI/NO

-   **vs_iniciacion_sexual_forzada_inducida (string):** vs - violencia sexual. Describe iniciación sexual forzada o inducida. Toma los valores SI/NO

-   **vs_otra_forma_violencia_sexual (string):** vs - violencia sexual. Describe otra forma de violencia sexual. Toma los valores SI/NO

-   **vs_no_sabe_no_contesta (string):** vs - violencia sexual. Describe de violencia sexual que se desconoce o que NO hace referencia a los campos mencionados anteriormente. Toma los valores SI/NO

-   **ofv_sentimiento_amenaza (string):** ofv - otras formas de violencia. Describe sentimiento de amenaza. Toma los valores SI/NO

-   **ofv_amenazas_explicitas (string):** ofv - otras formas de violencia. Describe amenazas explícitas. Toma los valores SI/NO

-   **ofv_violencia_fisica (string):** ofv - otras formas de violencia. Describe violencia física. Toma los valores SI/NO

-   **ofv_intento_ahorcar (string):** ofv - otras formas de violencia. Describe si trataron de ahorcar a la víctima. Toma los valores SI/NO

-   **ofv_intento_quemar (string):** ofv - otras formas de violencia. Describe si trataron de quemar a la víctima. Toma los valores SI/NO

-   **ofv_intento_ahogar (string):** ofv - otras formas de violencia. Describe si trataron de ahogar a la víctima. Toma los valores SI/NO

-   **ofv_amenaza_muerte (string):** ofv - otras formas de violencia. Describe si la víctima recibió amenazas de muerte. Toma los valores SI/NO

-   **ofv_uso_sustancias_psicoactivas (string):** ofv - otras formas de violencia. Describe si la víctima recibió sustancias psicoactivas. Toma los valores SI/NO

-   **ofv_intento_privacion_libertad (string):** ofv - otras formas de violencia. Describe intento de privación de libertad. Toma los valores SI/NO

-   **ofv_privacion_libertad (string):** ofv - otras formas de violencia. Describe privación de libertad. Toma los valores SI/NO

-   **ofv_uso_arma_blanca (string):** ofv - otras formas de violencia. Describe uso de arma blanca. Toma los valores SI/NO

-   **ofv_uso_arma_fuego (string):** ofv - otras formas de violencia. Describe uso de arma de fuego. Toma los valores SI/NO

-   **ofv_enganio_seduccion (string):** ofv - otras formas de violencia. Describe engaño o seducción. Toma los valores SI/NO

-   **ofv_intento_matar (string):** ofv - otras formas de violencia. Describe intento de asesinato. Toma los valores SI/NO

-   **ofv_uso_animal_victimizar (string):** ofv - otras formas de violencia. Describe la utilización de un animal para victimizar. Toma los valores SI/NO

-   **ofv_grooming (string):** ofv - otras formas de violencia. Describe Grooming. Toma los valores SI/NO

-   **ofv_otra_forma_violencia (string):** ofv - otras formas de violencia. Describe otra forma de violencia. Toma los valores SI/NO

-   **ofv_no_sabe_no_contesta (string):** vs - violencia sexual. Describe de otras formas de violencias que se desconocen o que no hacen referencia a los campos mencionados anteriormente. Toma los valores SI/NO


### Intervenciones domiciliarias por casos de abuso sexual - Línea 137 - AAAAMM

-   **Nombre del archivo:** intervenciones-domiciliarias-abuso-sexual-AAAA.csv

-   **Descripción del contenido:** detalle de las intervenciones domiciliarias por casos de violencia sexual efectuadas en CABA por el equipo móvil, luego de los llamados recibidos en la Línea 137/0800-222-1717 (ambas de alcance nacional). La unidad de análisis en este recurso es la víctima. Corresponde al período comprendido entre enero y el mes del año indicado en el título.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** detalle de las intervenciones realizadas desde enero de 2018 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **caso_id (int):** código que permite identificar el caso (este campo es publicado a partir del 1er. trimestre de 2020)

-   **intervención_fecha_hora (string):** fecha y hora en la que se realiza la intervención

-   **victima_edad (entero):** edad de víctima

-   **victima_convive_agresor: (string):** describe si la víctima convive con el agresor. Toma los valores:

    -   SI

    -   NO

-   **victima_embarazo (string):** describe si la víctima está embarazada: Toma los valores:

    -   SI

    -   NO

-   **victima_nacionalidad (string):** nacionalidad de la víctima

-   **victima_genero (string):** género de la víctima. Toma los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   NS/NC: No sabe / No contesta

-   **victima_discapacidad (string):** describe si la víctima posee algún tipo de discapacidad. Toma los valores:

    -   SI

    -   NO

-   **victima_vinculo_agresor (string):** describe el vínculo que tiene la víctima con el agresor (¿Qué es el agresor de la víctima?)

-   **vs_violacion_via_vaginal (string):** vs - violencia sexual. Describe violación vía vaginal. Toma los valores SI/NO

-   **vs_violacion_via_anal (string):** vs - violencia sexual. Describe violación vía anal. Toma los valores SI/NO

-   **vs_violacion_via_oral (string):** vs - violencia sexual. Describe violación vía oral. Toma los valores SI/NO

-   **vs_tentativa_violacion (string):** vs - violencia sexual. Describe tentativa de violación. Toma los valores SI/NO

-   **vs_tocamiento_sexual (string):** vs - violencia sexual. Describe tocamiento sexual. Toma los valores SI/NO

-   **vs_intento_tocamiento (string):** vs - violencia sexual. Describe intento de tocamiento. Toma los valores SI/NO

-   **vs_intento_violacion_tercera_persona (string):** vs - violencia sexual. Describe intento de violación por tercera persona. Toma los valores SI/NO

-   **vs_grooming (string):** vs - violencia sexual. Describe Grooming. Toma los valores SI/NO

-   **vs_exhibicionismo (string):** vs - violencia sexual. Describe exhibicionismo. Toma los valores SI/NO

-   **vs_amenazas_verbales_contenido_sexual (string):** vs - violencia sexual. Describe amenazas verbales con contenido sexual. Toma los valores SI/NO

-   **vs_explotacion_sexual (string):** vs - violencia sexual. Describe explotación sexual. Toma los valores SI/NO

-   **vs_explotacion_sexual_comercial (string):** vs - violencia sexual. Describe explotación sexual comercial. Toma los valores SI/NO

-   **vs_explotacion_sexual_viajes_turismo (string):** vs - violencia sexual. Describe explotación sexual en viajes de turismo. Toma los valores SI/NO

-   **vs_sospecha_trata_personas_fines_sexuales (string):** vs - violencia sexual. Describe sospecha de trata de personas con fines sexuales. Toma los valores SI/NO

-   **vs_existencia_facilitador_corrupcion_nnya (string):** vs - violencia sexual. Describe existencia de un facilitador a la corrupción de niños, niñas y adolescentes. Toma los valores SI/NO

-   **vs_obligacion_sacarse_fotos_pornograficas (string):** vs - violencia sexual. Describe si la víctima fue obligada a sacarse fotos pornográficas. Toma los valores SI/NO

-   **vs_eyaculacion_partes_cuerpo (string):** vs - violencia sexual. Describe la eyaculación en partes del cuerpo. Toma los valores SI/NO

-   **vs_acoso_sexual (string):** vs - violencia sexual. Describe acoso sexual. Toma los valores SI/NO

-   **vs_iniciacion_sexual_forzada_inducida (string):** vs - violencia sexual. Describe iniciación sexual forzada o inducida. Toma los valores SI/NO

-   **vs_otra_forma_violencia_sexual (string):** vs - violencia sexual. Describe otra forma de violencia sexual. Toma los valores SI/NO

-   **vs_no_sabe_no_contesta (string):** vs - violencia sexual. Describe de violencia sexual que se desconoce o que no hace referencia a los campos mencionados anteriormente. Toma los valores SI/NO

-   **ofv_sentimiento_amenaza (string):** ofv - otras formas de violencia. Describe sentimiento de amenaza. Toma los valores SI/NO

-   **ofv_amenaza_explicita (string):** ofv - otras formas de violencia. Describe amenazas explícitas. Toma los valores SI/NO

-   **ofv_violencia_fisica (string):** ofv - otras formas de violencia. Describe violencia física. Toma los valores SI/NO

-   **ofv_intento_ahorcar (string):** ofv - otras formas de violencia. Describe si trataron de ahorcar a la víctima. Toma los valores SI/NO

-   **ofv_intento_quemar (string):** ofv - otras formas de violencia. Describe si trataron de quemar a la víctima. Toma los valores SI/NO

-   **ofv_intento_ahogar (string):** ofv - otras formas de violencia. Describe si trataron de ahogar a la víctima. Toma los valores SI/NO

-   **ofv_amenaza_muerte (string):** ofv - otras formas de violencia. Describe si la víctima recibió amenazas de muerte. Toma los valores SI/NO

-   **ofv_uso_sustancias_psicoactivas (string):** ofv - otras formas de violencia. Describe si la víctima recibió sustancias psicoactivas. Toma los valores SI/NO

-   **ofv_intento_privacion_libertad (string):** ofv - otras formas de violencia. Describe intento de privación de libertad. Toma los valores SI/NO

-   **ofv_privacion_libertad (string):** ofv - otras formas de violencia. Describe privación de libertad. Toma los valores SI/NO

-   **ofv_uso_arma_blanca (string):** ofv - otras formas de violencia. Describe uso de arma blanca. Toma los valores SI/NO

-   **ofv_uso_arma_fuego (string):** ofv - otras formas de violencia. Describe uso de arma de fuego. Toma los valores SI/NO

-   **ofv_enganio_seduccion (string):** ofv - otras formas de violencia. Describe engaño o seducción. Toma los valores SI/NO

-   **ofv_intento_matar (string):** ofv - otras formas de violencia. Describe intento de asesinato. Toma los valores SI/NO

-   **ofv_uso_animal_victimizar (string):** ofv - otras formas de violencia. Describe la utilización de un animal para victimizar. Toma los valores SI/NO

-   **ofv_grooming (string):** ofv - otras formas de violencia. Describe Grooming. Toma los valores SI/NO

-   **ofv_otra_forma_violencia (string):** ofv - otras formas de violencia. Describe otra forma de violencia. Toma los valores SI/NO

-   **ofv_no_sabe_no_contesta (string):** ofv - otras formas de violencia. Describe de otras formas de violencias que se desconocen o que no hacen referencia a los campos mencionados anteriormente. Toma los valores SI/NO

### Linea 137 - violencia sexual - llamados atendidos e intervenciones realizadas

-   **Nombre:** linea 137-violencia-sexual-llamados-intervenciones.zip

-   **Descripción del contenido:** archivo comprimido conteniendo toda la información disponible de llamados e intervenciones, organizados en archivos anuales.

-   **Formato:** ZIP


Notas
-----

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Formulario de denuncia - Equipo Niñ@s contra la Explotación Sexual y Grooming del Programa Las Víctimas contra Las Violencias del Ministerio de Justicia de la Nación.](https://www2.jus.gov.ar/equipoNinos)


[Un análisis de los datos del Programa "Las Víctimas Contra Las Violencias" 2020-2021](http://datos.jus.gob.ar/varios/Victimas_Contra_Las_Violencias_2020-2021.pdf)


Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 187 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2018-187-APN-MJ.pdf), del 9 de Marzo de 2018.
