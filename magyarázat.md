A feladat az, hogy a megadott hitelfelvevők hitele mekkora eséllyel (valószínűség) fog bedőlni a vizsgált időszak utáni 2 évben. A cél esemény a bedőlés. A feladatot a következő lépésekben kell megoldani:

- housing loans, commodity loans, open-end loans and even credit card contracts.
- ingatlan hitel
- áru hitel - a mögötte lévő fedezet valami áru
- open-end loan - folyószámla hitel, hitelkártya - a hitelezett összeg újra felvehető
- credit card contracts - hitelkártya szerződés


| Adatmező                  | Leírás                                           | Dummy?                                         | Hiányzó értékek száma |
|--------------------------|--------------------------------------------------| ----------------------------------------------------------------- | --------------------- |
| CONTRACT_ID              | Szerződés azonosítója                             |-                                                            | 0                     |
| BORROWER_ID              | Hitelező azonosítója                              |- | 0                     |
| CONTRACT_BANK_ID         | A bank azonosítója, amely a szerződést kezeli     |!                                                        | 0                     |
| CONTRACT_CREDIT_INTERMEDIARY | Hitelközvetítő szám kategória?                |! | 59,422                |
| CONTRACT_CREDIT_LOSS     | A szerződés vesztesége - elszámolt, bedőlt, fennálló tartozás mértéke |-| 36,154 |
| CONTRACT_CURRENCY         | A szerződés valuta típusa                        |!| 0                     |
| CONTRACT_DATE_OF_LOAN_AGREEMENT | A kölcsönszerződés dátuma                 |?| 0                     |
| CONTRACT_DEPT_SERVICE_TO_INCOME | A tartozás szolgáltatása a jövedelemhez képest -  |-| 201,480 |
| CONTRACT_FREQUENCY_TYPE   | A szerződés gyakoriság típusa                    |! | 0                     |
| CONTRACT_INCOME          | A szerződés jövedelme - mekkora bevétel éri a bankot a szerződésből|- | 198,022               |
| CONTRACT_INSTALMENT_AMOUNT | A havi részlet összege - tőke? |- | 1,314,531             |
| CONTRACT_INSTALMENT_AMOUNT_2 | A második havi részlet összege - kamatrész? |- | 42,438                |
| CONTRACT_INTEREST_PERIOD | A kamatperiódus - ugyanaz mint frequency type? |? | 371,312               |
| CONTRACT_INTEREST_RATE   | A kamatláb                                      |- | 35,370                |
| CONTRACT_LGD             | A veszteség mértéke (Loss Given Default)         |- | 33,722                |
| CONTRACT_LOAN_AMOUNT     | A kölcsön összege                               |- | 0                     |
| CONTRACT_LOAN_CONTRACT_TYPE | A kölcsön szerződés típusa                  |! | 0                     |
| CONTRACT_LOAN_TO_VALUE_RATIO | A kölcsön-érték arány - hitelfedezetének az aránya a hitelhez képest |- | 1,176,530             |
| CONTRACT_LOAN_TYPE       | A kölcsön típusa                                |! | 0                     |
| CONTRACT_MARKET_VALUE    | A piaci érték - fedezet piaci értéke           |- | 1,074,843             |
| CONTRACT_MATURITY_DATE   | A lejárat dátuma                                |? | 0                     |
| CONTRACT_MORTGAGE_LENDING_VALUE | A jelzáloghitelezés értéke                |- | 1,064,936             |
| CONTRACT_MORTGAGE_TYPE   | A jelzálog típusa                               | !| 1,064,936             |
| CONTRACT_REFINANCED      | Refinanszírozott szerződés (igen/nem)           | !| 59,422                |
| CONTRACT_RISK_WEIGHTED_ASSETS | A kockázat súlyozott eszközei - jelzálog tárgy kockázata |?| 33,722                |
| CONTRACT_TYPE_OF_INTEREST_REPAYMENT | A kamat visszafizetés típusa             |! | 232,962               |
| BORROWER_BIRTH_YEAR      | Hitelező születési éve                           |! | 42,867                |
| BORROWER_CITIZENSHIP     | Hitelező állampolgársága                       |! | 42,867                |
| BORROWER_COUNTRY         | Hitelező országa                                |! | 42,867                |
| BORROWER_COUNTY          | Hitelező megyéje                                |! | 96,677                |
| BORROWER_TYPE_OF_CUSTOMER | Hitelező ügyfél típusa                        |! | 0                     |
| BORROWER_TYPE_OF_SETTLEMENT | Hitelező elhelyezkedés típusa                |? | 528,624              |
| TARGET_EVENT             | Cél esemény                                      |? | 0                     |
| TARGET_EVENT_DAY         | Cél esemény napja                               |? | 1,548,364             |
