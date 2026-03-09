# table of cars
| nome colonna | tipo di dato | attributi | indice |
| ------------ | ------------ | --------- | ------ |
|id| BIGINT|NOT NULL, UNIQUE, AUTO INCREMENT|PRIMARY KEY|
|marca-auto| VARCHAR(20)| NOT NULL| INDEX|
|modello-auto| VARCHAR(20)| NOT NULL| INDEX|
|targa| CHAR(7)| NOT NULL, UNIQUE| INDEX|
|numero-di-telaio| CHAR(17)| NOT NULL, UNIQUE||
|km percorsi| MEDIUMINT | NOT NULL, UNSIGNED||
|cilindrata-motore| MEDIUMINT|||
|tipo-di-motore| VARCHAR(50)| NOT NULL||
|tipo-di-combustibile| VARCHAR(15)|||
|tipo-di-cambio| VARCHAR(15)|||