# PerfilamientoClientes
En este repos se encuentra el uso de técnicas de análisis de datos descriptivos, con el objetivo de realizar segmentaciones poblacionales.
En este caso el objetivo es generar una estrategia de ventas de tarjeta de crédito, en el notebook se hace uso del archivo de datos "bdclientes.csv", la cual se le realiza el análisis de datos exploratorio para conocer y entender los datos, se realiza la selección de atributos relevantes: Se decide eliminar el atributo "Estudios", debido a que se considera que esta variable categórica no es determinante al momento de ofrecer un producto financiero. Nos interesan más datos como por ejemplo:
Tipo de ingresos: Pensionado, trabajador, o estudiante.
Edad
Saldo promedio: Para determinar una posible necesidad financiera.
Para el atributo "Estado Civil" se generan Variables Dummies, y se separan los datos en dos categorías mutuamente excluyentes,Casados y No Casados, debido a que no existe una diferencia significativa en términos del estado civil de una persona ya sea soltera, divorciada o viuda, pues cualquiera de estos está solo (no tiene conyuge).Además no existe diferencia significativa sí se está casado por lo civil o por lo religioso,como como es el caso entre los casados y no casado a la hora de hacer un análisis.
Posteriormente se normalizan los datos y se busca el numero optimo de clusters con la técnica del codo. 

Descripción de los grupos:

Grupo Comerciantes:

El 37% son hombres, todos son asesores comerciales, menos de la mitad (43%) tienen auto, la mayoría (70%) poseen alguna propiedad,menos de la mitad (47%) tienen hijos, la mayoría (77%) son casados y las personas de este grupo tienen ingreso anual promedio de 222224

Grupo Adultos pensionados:
El 20% son hombres,más de la mitad (68%) son pensionados, el 32% son servidores de estado, el 25% tienen auto, el 72% poseen alguna propiedad, el 20% tienen hijos y el 73% son casados,con ingreso anual promedio de 168911

Grupo Trabajadores activos:

El 38% son hombres,todos son trabajadores, el 40% tienen auto, el 67% poseen alguna propiedad, el 52% tienen hijos y el 78% son casados,con ingreso anual promedio de 181256

Estrategia Comercial
Como en el grupo Comerciantes, la mayoría de personas son asesores comerciales, tienen un promedio de ingresos alto, gran parte tienen propiedades, y son casados una posible necesidad financiera puede ser la de adquirir una cuenta corriente debido a las transacciones que como comerciantes pueden realizar en su cotidianidad, además, posiblemente les interese acceder a un crédito hipotecario para adquirir un inmueble comercial como local u oficina, como oportunidad de expansión de sus lineas comerciales. Como este grupo es el que mayor proporción de automoviles tiene, también es importante tener en cuenta que es de gran utilidad un seguro automoviliístico contra todo riesgo.

Para el grupo Adultos pensionados en los cuales la mayoría son pensionados, tienen ingresos promedio buenos y posiblemente tengan una edad adulta, no tienen la necesidad de hacer muchas transacciones, por lo general, lo que estas personas hacen usualmente es simplemente tener una cuenta de ahorros donde se les deposita su nomina de pensión. A estas personas les puede interesar mucho más un certificado de depósito a término (CDT), para que sus ahorros les genere intereses mientras pasan su vejez.

En el grupo Trabajadores activos se encuentra el grupo que mayor proporción de hombres tiene con respecto a los anteriores, en donde gran parte de estos son trabajadores activos, por lo tanto tienen un nivel de ingresos muy bueno, además gran proporción posee familia y están casados. Una buena oportunidad para este grupo puede ser la de ofrecerles un seguro de vida el cual, les dará la confianza de que al realizar trabajos que signifiquen algún tipo de peligro, puedan tener a su familia y patrimonio respaldado, además sería atractivo un credito de vacaciones familiares, posiblemente les quieran llevar a su familia de vacaciones y compartir experiencias en lugares turísticos, además de una tarjeta de crédito que puede ayudarle a sus finanzas a apalancarse debido a su respaldo que tiene con las propiedades y sus buenos ingresos.
