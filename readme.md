<!--

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
come visto in classe fai un file readme.md
inserisci nome della tabella,
inserisci le colonne per definire il modello
assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
PUSHA

 -->

## Table ` used_cars`

## Table columns

| Colonna  
|
| `id` - BIGINT - PRIMARY KEY, AUTO_INCREMENT, NOT NULL  
| `brand` - VARCHAR(100) - NOT NULL  
| `model` - VARCHAR(100) - NOT NULL  
| `year` - YEAR - NOT NULL  
| `mileage` - INT - NOT NULL  
| `fuel_type` - VARCHAR(50) - NOT NULL  
| `transmission` - VARCHAR(50) - NOT NULL  
| `color` - VARCHAR(50) - NOT NULL  
| `price` - DECIMAL(10,2) - NOT NULL  
| `is_available` - TINYINT - DEFAULT 1  
| `condition` - VARCHAR(50) - NULL  
| `vin` - CHAR(17) - NOT NULL  
| `number_of_owners` - TINYINT - NULL  
| `engine_size` - DECIMAL(4,1) - NULL  
| `power_hp` - SMALLINT | NULL  
| `emission_class` - VARCHAR(20) - NULL  
| `registration_city` - VARCHAR(100) - NULL  
| `car_type` - VARCHAR(50) - NULL  
| `doors` - TINYINT - NULL  
| `seats` - TINYINT - NULL  
| `photos_url` - VARCHAR(255) - NULL  
| `warranty_months` - SMALLINT - DEFAULT  
| `description` - TEXT - NULL  
| `created_at` - DATETIME - NOT NULL  
| `updated_at` - DATETIME - NULL
