
| nome colonna | tipo di dato | attributi |
| ---- | ---- | ---- |
| id | INT | primary key, auto_increment |
| tipo_macchina | VARCHAR(20) | -- |
| marca_macchina | VARCHAR(20) | -- |
| tipo_marca | VARCHAR(20) | -- |
| prezzo | int | -- |
| anno_macchina_fabbricazione | DATE | -- |
| qualita_macchina | tinyint(5) | default(5) |
| neopatentati | BOOLEAN | notnull |
| tipo_carburante | VARCHAR(15) | -- |
| tipo_cambio | VARCHAR(15) | -- |
| telecamere_per_parcheggio | BOOLEAN | notnull |
| display_digitale_per_autista | BOOLEAN | notnull |
| discount | TINYINT | default(0) |
| acquisto_a_rate | BOOLEAN | notnull |
| assistenza_per_cliente | VARCHAR(15) | -- |
| consegna_a_domicilio | BOOLEAN | notnull |
| test_drive | BOOLEAN | notnull |
| tagliando | VARCHAR(15) | -- |

