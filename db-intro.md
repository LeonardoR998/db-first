# Concessionario

| name                  | type         | attributes                          | key     |
| --------------------- | ------------ | ----------------------------------- | ------- |
| id                    | BIGINT(20)   | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |
| car chassis code      | CHAR(17)     | NOT NULL - UNIQUE                   | NONE    |
| brand                 | VARCHAR(15)  | NOT NULL                            | NONE    |
| conditions            | CHAR(1)      | NOT NULL                            | NONE    |
| car year              | VARCHAR(10)  | NOT NULL                            | NONE    |
| km                    | SMALLINT     | NOT NULL - UNSIGNED                 | NONE    |
| car type              | SMALLINT     | NULL                                | NONE    |
| car registration year | VAR CHAR(10) | NULL - UNSIGNED                     | NONE    |
