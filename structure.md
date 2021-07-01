# Database Cars

## (table) Cars:

- id                                    BIGINT          PRIMARY KEY UNIQUE INDEX
- marca                                 VARCHAR(20)     NOTNULL INDEX
- modello                               VARCHAR(20)     NOTNULL INDEX
- versione                              VARCHAR(20)     NOTNULL
- carrozzeria (city-car, berlina, ecc.) VARCHAR(20)     NULL     
- motore                                VARCHAR(10)     NOTNULL INDEX          
- cavalli                               VARCHAR(4)      NULL
- cilindrata                            VARCHAR(10)     NOTNULL
- anno di immatricolazione              YEAR            NOTNULL
- foto                                  VARCHAR(255)    NULL
- nuovo                                 TINYINT <!-- VERO O FALSO --> NULL
- usato                                 TINYINT <!-- VERO O FALSO --> NULL
- km zero                               TINYINT <!-- VERO O FALSO --> NULL
- Chilometraggio                        VARCHAR(7)      NULL   
- prezzo massimo                        DECIMAL(8,2)    NULL
- paese di provenienza                  VARCHAR(15)     NULL
- n. di porte                           TINYINT         NULL
- n. di posti                           TINYINT         NULL
- garanzia                              TINYINT <!-- VERO O FALSO --> NULL
- tagliandi certificati                 TINYINT <!-- VERO O FALSO --> NULL
- veicolo danneggiato                   TINYINT <!-- VERO O FALSO --> NULL
- garanzia ufficiale                    TINYINT <!-- VERO O FALSO --> NULL