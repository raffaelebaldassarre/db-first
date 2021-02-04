<!-- Creazione di un database di un negozio di videogiochi. -->

# database name: Negozio

# nome tabelle: Videogiochi

- id BIGINT PRIMARYKEY
- titolo string VARCHAR (50) NOTNULL
- descrizione TEXT NULL
- genere string VARCHAR(15) NOTNULL
- anno_di_pubblicazione data YEAR NOTNULL
- edizione string VARCHAR(20) NULL
- prezzo number FLOAT(5,2) NULL
- disponibilità number TINYIT NULL DEFAULT(0) non c'è
- quantità number SMALLINT NULL DEFAULT(0)
- lingua string VARCHAR(20) NOTNULL
- immagine_copertina string VARCHAR(250) NULL
- creators string VARCHAR(30) NOTNULL
- creator rules VARCHAR(30) NOTNULL
- publishers string VARCHAR(25) NULL
- materiale_copertina string VARCHAR(25) NULL
- formato string VARCHAR(25) NULL
- platform string VARCHAR(25) NULL
- created data DATETIME NOTNULL
- edited data DATETIME NULL
