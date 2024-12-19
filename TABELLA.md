# Car table

| name               | type        | attributes                          | key     | notes                                       |
| ------------------ | ----------- | ----------------------------------- | ------- | ------------------------------------------- |
| id                 | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |                                             |
| brand              | CHAR(20)    | NOT NULL                            |         |                                             |
| model              | CHAR(20)    | NOT NULL                            |         |                                             |
| registered_at      | DATE        | NOT NULL                            |         |                                             |
| mileage            | INT         | NOT NULL                            |         |                                             |
| engine type        | CHAR(20)    | NOT NULL                            |         |                                             |
| color              | CHAR(20)    | NULL                                |         |                                             |
| bodywork condition | CHAR(1)     | NOT NULL                            |         | (p) -> pessime, (m) -> medie, (o) -> ottime |
| price              | FLOAT(8, 2) | NOT NULL                            |         |                                             |
