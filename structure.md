<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# Concessionario

## (Table) auto_usate:

- id | BIGINT - PRIMARY KEY AUTO INCREMENT UNIQUE, NOTNULL
- marca_auto | VARCHAR(255) - NOTNULL
- modello_auto | VARCHAR(255) - NOTNULL
- colore | VARCHAR(50) - NULL
- anno_immatricolazione | YEAR - NULL
- km_percorsi | MEDIUMINT - NULL
- alimentazione | VARCHAR(20) - NULL
- cilindrata_motore | VARCHAR(10) - NULL
- potenza | VARCHAR(10) - NULL
- classe_emissione | VARCHAR(10) - NULL
- carrozzeria | VARCHAR(255) - NULL
- posti_disponibili | TYNYINT - NULL
- numero_porte | TYNYINT - NULL
- cambio | VARCHAR(20) - NULL
- prezzo | MEDIUMINT - NULL
- sconto | TYNYINT - NULL
- neopatentati | TYNYINT - DEFAULT(1)
- immagine_auto | VARCHAR(255) - NULL
- numero_proprietari | TYNYINT - NULL
- note | TEXT - NULL

- (?) consumi_carburante | VARCHAR(50) - NULL
- (?) equipaggiamenti | TEXT - NULL
