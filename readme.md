Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Nome DataBase concessionario_Me

# Colonne

id (#1) / NOT NULL / AUTOINCREMENT  / OBBLIGATORIO

marca_Auto (es Bmw, Audi) / VARCHAR  / NOT NULL

nome_Auto (es X1, A3) / VARCHAR / NOT NULL

modello_Auto ( es Suv, Berlina) / VARCHAR / NULL

motorizazzione_Auto ( es Diesel, Benzina, Elettrica) / VAR CHAR /  NULL

kilometri_Auto ( es 10.000 km - 50.000) / MEDIUMINT(999999) / NULL

trasmissione_Auto (es Automatica, Manuale , Sequenziale) /VARCHAR(500) / NULL 

potenza_Auto (es 150cv), SMALLINT / NULL
    
Kilowatt_Auto (es 85 kw), SMALLINT / NULL    

cilindrata_Auto (es 2000 , 1500 ) SMALLINT / NULL

anno_immatricolazione ( es 8/2021 10/2022) / DATE / NULL

accessori_auto (es fari - clima - sedili )  / TEXT / NULL

porte_auto (es tre o cinque porte) / TINYTEXT / NULL 

garanzia_Auto (es garanzia bmw, audi o garanzia concessionario) / TEXT / NULL

condizioni_Auto ( es usata, km zero, promo ) / TEXT / NULL

emissioni_Auto (es Euro 5 - Euro 6 **Molto importante per le normale che impediscono la circolazione**) VARCHAR / NULL

colore_Auto (es blu, bianca) TINYTEXT / NULL

prezzo_Auto (es €19.000 - € 35.000 ) / DOUBLE(9,2) / NULL

finanziamento_Auto (es finanziabile si/no (passa in sede per scoprirlo)) VARCHAR / NULL





