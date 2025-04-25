```mermaid
classDiagram
  class BankAccount {
    -string m_customerName
    -double m_balance
    +Debit(amount)
    +Credit(amount)
    +Balance
  }
```
