<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# Concessionario

## (Table) auto_usate:

- id | BIGINT
- marca_auto | VARCHAR(255)
- modello_auto | VARCHAR(255)
- colore | VARCHAR(50)
- anno_immatricolazione | YEAR
- km_percorsi | MEDIUMINT
- alimentazione | VARCHAR(20)
- cilindrata_motore | VARCHAR(10)
- potenza | VARCHAR(10)
- classe_emissione | VARCHAR(10)
- carrozzeria | VARCHAR(255)
- posti_disponibili | TYNYINT
- numero_porte | TYNYINT
- cambio | VARCHAR(20)
- prezzo | MEDIUMINT
- sconto | TYNYINT
- neopatentati | TYNYINT
- immagine_auto | VARCHAR(255)
- numero_proprietari | TYNYINT
- note | TEXT

- (?) consumi_carburante | VARCHAR(50)
- (?) equipaggiamenti | TEXT
