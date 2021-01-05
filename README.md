# PRA 2 - Neteja i anàlisi de les dades

Repositori amb els arxius creats i obtinguts durant la pràctica 2.

# Membres de l'equip

L'activitat ha estat realitzada de manera conjunta per Aleix Borrella Colomé (aborrellac) i Albert Gil Devesa (agildeve).

# Descripció

Hem realitzat aquest exercici pràctic en el marc de l'assignatura de Tipologia i cilce de Vida de les Dades, assignatura de caràcter obliatori corresponent al Màster en Ciència de Dades de la Universitat Oberta de Catalunya (UOC). Com a exemple de la pràctia de l'anomenat Web Scraping, hem realitzar un conjunt de scrips de Python emprant les llibreries de BeautifulSoup i requests per capturar la informació de productes continguda a la web del supermercat on-line de Bonpreu-Esclat. Hem afegit el camp "data", per poder realitzar anàlisis temporals de la evolució de preus, de la quantitat de productes ofertats o la durada de ofertes, per exemple.

# Codi:

- Scripts/main.py: Primerament executa el "get_urls.py" per tenir una llista de totes les urls corresponents a categories finals. Un cop ja té totes les urls, executa "scraper.py" per capturar tota la informació referent als productes trobats. Finalment concatena tota la informació i ho guarda com a arxiu '.csv' amb data del dia en que s'ha realitzat la captura.

- Scrips/get_urls.py: Navega a través de les categories de Bonpreu-Esclat cercant totes les urls amb categories finals, i retorna una llista amb totes les urls finals.

- Scripts/scraper.py: Realitza web scraping a una url del supermercat on-line Bonpreu-Esclat i retorna un DataFrame amb la següent informació capturada:
    - Primera categoria de classificació.
    - Segona categoria de classificació.
    - Tercera categoria de classificació.
    - Quarta categoria de classificació.
    - Cinquena categoria de classificació.
    - Nom del producte.
    - Preu del producte.
    - La quantitat de producte.
    - Cost del producte normalitzat (preu per quilo/litre).
    - Si el producte està en oferta o promoció.
    - Descripció de la promoció a la qual està subjecta el producte.
    - URL del producte.
    - Data en la que s'ha pres la mostra.

- Scripts/concat.py: Busca tots els arxius '.csv' que hi ha al mateix directori i els unifica en un sol dataset final. Si hi ha un '.csv' amb el nom designat al resultat l'ignorem.

# Respostes:

Conté varies mostres preses durant la setmana del 02/11/2020 al 06/11/2020:
- Dataset/20201102_BP_dataset.csv: Mostra corresponent al 02/11/2020.
- Dataset/20201103_BP_dataset.csv: Mostra corresponent al 03/11/2020.
- Dataset/20201104_BP_dataset.csv: Mostra corresponent al 04/11/2020.
- Dataset/20201105_BP_dataset.csv: Mostra corresponent al 05/11/2020.
- Dataset/20201106_BP_dataset.csv: Mostra corresponent al 06/11/2020.
- Dataset/Datasets_setmanals.zip: Arxiu comprimit que conté els 5 arxius .csv anteriors per tal d'agilitzar-ne la descarrega
    
Arxiu final obtingut executant concat.py (tots els arxius han d'estar al mateix directori):
- BP_dataset.csv
    
# Dataset Inicial:

# Datasets Finals:






Apunts proporcionats en l’aula:

- El llenguatge Python - David Masip Rodó
- Web Scraping - Laia Subirats Maté i Mireia Calvo González
- Web Scraping with Python – Chapter 2: Scraping the data – Lawson, R
- Automated Data Collection with R – S. Munzert, C. Rubba, P. Meibner i D. Nyhuis

Altres recursos:
