# Projeto 06 - EDA da Grifinória

**Banco de dados utilizado foi retirado do Kaggle:**

- **Título:** Should This Loan be Approved or Denied?
- Um dataset grande e rico do **U.S. Small Business Admistration (SBA)**
- [Link do Kaggle](https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied?resource=download)

## Análise dos tipos de variáveis

| Coluna            | Tipo da variável                   |                                           Descrição |
| :---------------- | :--------------------------------- | --------------------------------------------------: |
| LoanNr_ChkDgt     | Quantitativa Discreta              |                              Identifier Primary key |
| Name              | Qualitativa Nominal                |                                       Borrower name |
| City              | Qualitativa Nominal                |                                       Borrower city |
| State             | Qualitativa Nominal                |                                      Borrower state |
| Zip               | Qualitativa Nominal                |                                   Borrower zip code |
| Bank              | Qualitativa Nominal                |                                           Bank name |
| BankState         | Qualitativa Nominal                |                                          Bank state |
| NAICS             | Qualitativa Ordinal                |  North American industry classification system code |
| ApprovalDate      | Qualitativa Ordinal                |                          Date SBA commitment issued |
| ApprovalFY        | Quantitativa Discreta              |                           Fiscal year of commitment |
| Term              | Quantitativa Discreta              |                                 Loan term in months |
| NoEmp             | Quantitativa Discreta              |                        Number of business employees |
| NewExist          | Qualitativa Nominal                |             1 = Existing business, 2 = New business |
| CreateJob         | Quantitativa Discreta              |                              Number of jobs created |
| RetainedJob       | Quantitativa Discreta              |                             Number of jobs retained |
| FranchiseCode     | Qualitativa Nominal                |     Franchise code, (00000 or 00001) = No franchise |
| UrbanRural        | Qualitativa Nominal                |                 1 = Urban, 2 = rural, 0 = undefined |
| RevLineCr         | Qualitativa Nominal                |           Revolving line of credit: Y = Yes, N = No |
| LowDoc            | Qualitativa Nominal                |                LowDoc Loan Program: Y = Yes, N = No |
| ChgOffDate        | Qualitativa Ordinal                |   The date when a loan is declared to be in default |
| DisbursementDate  | Qualitativa Ordinal                |                                   Disbursement date |
| DisbursementGross | Quantitativa Contínua              |                                    Amount disbursed |
| BalanceGross      | Quantitativa Contínua              |                            Gross amount outstanding |
| MIS_Status        | Qualitativa Nominal                | Loan status charged off = CHGOFF, Paid in full =PIF |
| ChgOffPrinGr      | Quantitativa Quantitativa Contínua |                                  Charged-off amount |
| GrAppv            | Quantitativa Quantitativa Contínua |               Gross amount of loan approved by bank |
| SBA_Appv          | Quantitativa Quantitativa Contínua |            SBA’s guaranteed amount of approved loan |
