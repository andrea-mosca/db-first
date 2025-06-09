| name           | type                                                               | attributes                         | index       |
| -------------- | ------------------------------------------------------------------ | ---------------------------------- | ----------- |
| id             | BIGINT                                                             | NOT NULL, AUTO_INCREMENT, UNSIGNED | PRIMARY KEY |
| brand          | VARCHAR(25)                                                        | NOT NULL                           |             |
| model          | VARCHAR(150)                                                       | NOT NULL                           | INDEX       |
| price          | DECIMAL(10,2)                                                      | NOT NULL, UNSIGNED                 |             |
| published_year | YEAR                                                               | NOT NULL                           |             |
| condition      | ENUM("excellent","very good", "good", "fair", "poor")              | NOT NULL                           |             |
| mileage        | INT                                                                | NOT NULL, UNSIGNED                 |             |
| fuel_type      | ENUM("gasoline", "diesel", "electric", "hybrid", "gpl", "methane") | NOT NULL                           |             |
| transmission   | ENUM("automatic", "manual")                                        | NOT NULL                           |             |
| has_accident   | BOOLEAN                                                            | NOT NULL, DEFAULT(0)               |             |
