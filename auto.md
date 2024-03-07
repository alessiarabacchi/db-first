## `AutoUsate` TABLE STRUCTURE

| FIELD          | TYPE          | ATTRIBUTES               | INDEXES     |
| -------------- | ------------- | ------------------------ | ----------- |
| id             | INT           | UNSIGNED, AUTO_INCREMENT | PRIMARY KEY |
| marca          | VARCHAR(50)   | NOT NULL                 |             |
| modello        | VARCHAR(50)   | NOT NULL                 |             |
| anno           | YEAR          |                          |             |
| chilometraggio | INT           | UNSIGNED                 |             |
| prezzo         | DECIMAL(10,2) | UNSIGNED                 |             |

---
