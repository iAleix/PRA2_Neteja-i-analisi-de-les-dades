# PRA 2 - Neteja i anàlisi de les dades

Repositori amb els arxius creats i obtinguts durant la pràctica 2.

# Membres de l'equip

L'activitat ha estat realitzada de manera conjunta per Aleix Borrella Colomé (aborrellac) i Albert Gil Devesa (agildeve).

# Descripció

Hem realitzat aquest exercici pràctic en el marc de l'assignatura de Tipologia i cilce de Vida de les Dades, assignatura de caràcter obliatori corresponent al Màster en Ciència de Dades de la Universitat Oberta de Catalunya (UOC). En ell s’elabora un cas pràctic orientat a aprendre a identificar les dades rellevants per un projecte analític i usar les eines d’integració, neteja, validació i anàlisi de les mateixes.

Per fer-ho, hem utilitzat el dataset “Novel Corona Virus 2019 Dataset - Day level information on Covid-19 affected cases” que es pot trobar a Kaggle en el següent enllaç: “https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset”, a partir del qual hem realitzat una integració i selecció de dades, neteja i tractament de valors nuls i extrems, així com 4 mètodes d'anàlisi diferents: una primera aplicació de tests estadístics, un càlcul de correlacions entre variables, una classificació de les dades a tavés de clustering i una regressió lineal multivariant.

# Codi:

En aquesta pràctica hem utiltizat R com a llenguatge de programació i també RMarkdown per generar un fitxer fàcil de llegir i al mateix disponible en diferents formats d'exportació. Com a complement, hem utilitzat la bibliografia "scholar.bib" per donar format a les dades de sortida de R.

El codi sencer que s'ha obtingut és troba en el fitxer "PRA 2 - Entrega.Rmd". Si es desitja obrir-lo amb RStudio i executar-lo, caldrà situar en una mateixa carpeta l'arxiu "PRA 2 - Entrega.Rmd", la bibliografia "scholar.bib", així com el dataset original "covid_19_data.csv".

# Respostes:

Com hem comentat, en utilitzar RMarkdown hem anat resolent els diferents punts proposats en l'enunciat d'aquesta pràctica directament en l'arxiu de codi, en el qual també es poden anar veient les sortides que genera. Una vegada acabat, l'hem exportat en diferents formats per tal de poder-lo consultar de la forma més còmode. D'aquesta manera, en la carpeta "Respostes" hi trobareu les solucions en 3 formats diferents: "PRA 2 - Entrega.html", "PRA 2 - Entrega.pdf" i "PRA 2 -Entrega.docx", tot i que recomenem utilitzar el format .html ja que és en el que millor es poden veure els resultats.

En les solucions també s'hi pot observar la taula de contribucions al treball, la qual ha signat cada integrant del grup amb les seves inicials. A més, per si es requereix, també la hem incorporat com un fitxer addicional, el qual es troba també dins la carpeta "Respostes" amb el nom "PRA 2 - Taula de contribucions.pdf".
    
# Dataset Inicial:

Aquesta pràctica partia del dataset “Novel Corona Virus 2019 Dataset - Day level information on Covid-19 affected cases” que es pot trobar a Kaggle en el següent enllaç: “https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset”, així que el fitxer .csv original és el que es troba en aquesta carpeta amb el nom de "covid_19_data.csv".

# Datasets Finals:

Tal i com hem indicat en la introducció, a partir del dataset original s'han integrat, seleccionat i netejat les dades per a posteriorment realitzar-ne 4 mètodes d'anàlisi diferents. En cada anàlisi s'ha obtingut un o més datasets resultants diferents, els quals es troben agrupats en funció de l'anàlisi realitzat en aquesta carpeta. L'esquema dels datasets finals obtinguts és el següent:

1. Test estadístics

- Europe.csv
- France.csv
- France_by_week.csv
- France_test.csv
- Italy.csv
- Italy_by_week.csv
- Italy_test.csv

2. Correlació

- start_covid_spain.csv
- end_covid_spain.csv
- covid_spain_normal.csv

3. Clustering

- covid_spain_normal.csv

4. Regressió

- Spain_test.csv

# Apunts proporcionats en l’aula:

- Introductory statistics with R - Peter Daalgard
- Introducció a la neteja i anàlisi de dades - Mireia Calvo González, Diego Oswaldo Pérez Trenard i Laia Subirats Maté
- Clean Data - Megan Squire
- Data Cleaning Basics: Best Practices in Dealing with Extreme Scores - Jason W. Osborne
- Data mining concepts and techniques - Morgan Kaufmann
