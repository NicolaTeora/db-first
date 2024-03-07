# DB-FRIST

Modellizzare la struttura di una tabella per memorizzare
tutti i dati riguardanti delle auto usate messe in vendita
da un concessionario

| PRIMARY_KEY  | TYPE_DATA   | ATTRIBUTES                      |
| ------------ | ----------- | ------------------------------- |
| ID           | INT         | AUTO_INCREMENT; UNIQUE; NOTNULL |
| NAME_CAR     | VARCHAR(25) | NOTNULL                         |
| MODEL_CAR    | VARCHAR(25) | NULL; DEFAULT("ask for info")   |
| YEAR         | YEAR        | NULL; DEFAULT("ask for info")   |
| KM           | SMALLINT    | NULL                            |
| PRICE        | FLOAT(6,2)  | NOTNULL                         |
| FUEL         | CHAR        | NULL                            |
| TRANSMISSION | CHAR        | NOTNULL                         |
