# Cesar-s-Portfolio
Portafolio de Análisis de Datos
# Proyecto: Análisis Financiero con Expresiones LOD (Level of Detail)
Las expresiones de nivel de detalle (LOD) permiten calcular fácilmente agregaciones que no tienen el nivel de detalle de la visualización. Posteriormente, estos valores se pueden agregar en las visualizaciones de forma arbitraria. Lo cual permite la elaboración de análisis que ofrecen información más especifica y que interrelaciona datos diferentes.
A continuación se detallan algunas herramientas de visualización utilizando expresiones LOD en Tableau y desarrolladas utilizando una base de datos ficticia que simula la operación de una tienda de artículos de oficina en Canadá y Estados Unidos, ofreciendo datos como órdenes de compra, clientes, productos, ventas y ubicación de las ventas.
Los títulos de cada herramienta desarrollada han sido vinculados a Tableau Public, donde se puede interactuar con las visualizaciones que así lo permitan.
## [1.- Análisis de Frecuencia de las Ordenes de los Clientes](https://public.tableau.com/views/1_-AnalissLODFrecuenciadeOrdenesdeClientes/FRECUENCIADEORDENESDECLIENTES?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
### ¿Cuántos clientes han hecho 1, 2, 3,…, n órdenes de compra?
![](Images/T1.png)
Calcular el número de pedidos que ha realizado cada cliente es relativamente fácil, pero ¿qué sucedería si quisiéramos saber cuántos clientes hicieron uno, dos, tres, etc.? Para crear esta vista, se desglosa el número de clientes por el número de pedidos realizados con ayuda de expresiones LOD.
## [2.- Análisis de Generación(Cohort Analysis)](https://public.tableau.com/views/2_-AnlisisLODGeneracindeClientesCohortAnalysis/DASHBOARDANLISISDEGENERACIN?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
### ¿Cuánto contribuye a la ganancia cada generación anual de clientes?
La visualización a continuación agrupa a los clientes por generaciones de acuerdo con el año de su primera compra para comparar las contribuciones a las ventas anuales entre ellas. La fecha mínima de pedido por cliente indicará la fecha de la primera compra y por tanto, la adquisición de dicho cliente. Dado que los datos de la visualización no se muestran por cliente, debemos usar una expresión LOD para fijar la fecha mínima de pedido por cliente.
## [3.- KPI de Rentabilidad Diaria](https://public.tableau.com/views/3_-AnlisisLODKPIdeRentabilidadDiaria/KPIGANANCIASDIARIAS?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
### ¿Cuántos días de cada de mes fueron redituables, poco redituables y en cuales hubo pérdidas?
Es usual visualizar las tendencias de ganancias a lo largo del tiempo, pero ¿qué sucede si medimos nuestro éxito según la ganancia total por día hábil? Podemos saber el número de días rentables logrados cada mes o año, especialmente si nos interesan los efectos estacionales. Las expresiones LOD nos permiten crear fácilmente intervalos con datos agregados, como la ganancia diaria, mientras que los datos subyacentes se registran a nivel transaccional. 

