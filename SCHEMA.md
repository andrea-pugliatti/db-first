# Table name: Cars (entity name: Car)

Columns:
- id            BIGINT PRIMARY KEY AUTO_INCREMENT NOT NULL
- title         VARCHAR(200) NOT NULL
- model         VARCHAR(100) NOT NULL
- car_make      VARCHAR(20) NOT NULL
- mileage       SMALLINT NOT NULL
- colour        VARCHAR(20) NULL
- gearbox       VARCHAR(10) NULL
- power         SMALLINT NULL
- fuel_type     VARCHAR(10) NULL
- license_plate VARCHAR(10) NOT NULL
- registration  DATE NULL
- price         MEDIUMINT NOT NULL
- description   TEXT NULL
- created_at    DATETIME DEFAULT(now())