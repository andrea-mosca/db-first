| name           | type                                                             | attributes               | index       |
| -------------- | ---------------------------------------------------------------- | ------------------------ | ----------- |
| id             | BIGINT                                                           | NOT NULL, A.I., UNSIGNED | PRIMARY KEY |
| brand          | VARCHAR(25)                                                      |                          |             |
| model          | VARCHAR(150)                                                     |                          | INDEX       |
| price          | INT UNSIGNED                                                     |                          |             |
| published_year | YEAR                                                             | NULL                     |             |
| condition      | ENUM("excellent","very good", "good", "fair", "poor")            |                          |             |
| mileage        | INT UNSIGNED                                                     |                          |             |
| fuel_type      | ENUM("gasoline", "diesel", "electic", "hybrid", "gpl", "methan") |                          |             |
| trasmission    | ENUM("automatic", "manual")                                      |                          |             |
