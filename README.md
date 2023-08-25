# PROYECTO II
# *Cryptocurrency Market Data Analytics*

Las inversiones en criptomonedas, al igual que otros tipos de mercados, pueden ser incierto. El mercado está lleno de factores que no pueden ser controlados o predecibles a simple vista. Sin embargo, en el mundo de las criptomonedas es posible definir a ciertos rasgos cuando una moneda tiene alto riesgo o por el contrario altas posibilidades de ganancia. Para ello, es necesario un análisis fundamental que observe desde la ideología del proyecto hasta sus rendimientos financieros; volumen del mercado, volatilidad, precio, capitalización, etc. 

Uno de los factores influyentes en el mercado de las criptomonedas son las tendencias sociales. En estos años ha sido el tema de la inteligencia artificial.
Este proyecto se propone a realizar un análisis de la viabilidad de invertir en monedas basadas en proyectos de la IA. Este tiene como objetivo mostrarle a un potencial inversor las oportunidades o riesgos al invertir en una de las monedas basadas en proyectos en tendencia.

Es importante resaltar que uno de los retos al analizar una moneda en tendencia es su poca trayectoria en el mercado, los datos más antiguos que se tienen son del  año 2018 (solo 5 años de datos históricos). Aun así, los datos disponibles nos dan información sobre la tendencia alcistas o bajistas que puede tener la moneda. 

## Análisis de los Datos

**El análisis de los datos se realizó mediante la extracción de datos de la API de Coingecko a través de Python donde se hizo un trabajo de ETL y EDA, en este informe solo se presentará algunas partes del EDA.** 

Las 10 monedas seleccionadas fueron las siguientes: SingularityNet, Akash Network, Fetch.AI, Injective Protocol, The Graph, Insure DeFi, Oasis Network, Ocean Protocol, OriginTrail y Render.  Las cuales se basan en proyectos de IA, machine learning, servicios en la nube e intercambios descentralizados. 

Durante el análisis de los datos se observó que las monedas no siguen una sola lógica de comportamiento, es decir, tienen tendencias distintas dependiendo el contexto. En algunos casos influye que no tengan máximo de circulación o en otras influye el nivel de transacciones en determinados periodos. En este sentido, cuando se realiza la comparación volumen-precio se observa que algunas pueden tener tendencia alcistas mientras que otras con debilidad en el mercado. 

### KPI´s

Lo indicadores claves para evaluar la viabilidad de inversiones en este proyecto será:

-	KPI de rentabilidad: Mide cuanto tiene que subir la capitalización de mercado para obtener una rentabilidad mínima en la inversión. 
-	KPI relación volumen-precio: Mide cuando es viable invertir según la relación volumen-precio;
       -	Cuando el volumen sube y el precio sube se considera que es viable invertir porque  las personas están dispuestas a pagar más por la moneda (Refleja que la demanda supera la oferta y que la tendencia es alcista)
       -	Cuando el volumen baja y el precio sube alerta que hay pocos compradores (participación baja y tendencia débil)
       -	Cuando el precio baja y el volumen sube indica que hay compradores que están dispuestos a aceptar menos por cada moneda (la oferta supera la demanda y la tendencia es bajista)
       -	Cuando el precio y el volumen está en la misma dirección, así sea bajo, indica que el mercado puede crecer en los próximas temporadas.



