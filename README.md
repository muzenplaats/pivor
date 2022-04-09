# pivor v0.1.0-lambda
The pivor (巧樞) is an ingenious pivoting app for personal usages.

## Introduction
The pivor is a utility tool amid for the digested financial system in person.
It is based on the individual economics. The first step is to recall the
indifference curve.

The develpment is ongoing.

## Development

### Modeling
**i) Accounting Table**
```
=====================================================================
    Name     Amount   Unit    Price     Date              Note
---------------------------------------------------------------------
Cigarettes      1    package   95   Apr. 9, 2022   The first account
Cigarettes      1    package   95   Apr. 10, 2022  The first account
...
=====================================================================
```

**ii) Bank Checkout Table**
```
=====================================================================
Bank Name       Debit*   Credit*  Total*    Check Date       Note
---------------------------------------------------------------------
First Bank       1000       500     500    Apr. 9, 2022   Fake check
Second Bank       600     2,000  -1,400    Apr. 9, 2022   Fake check
...
=====================================================================
*Since last check.
```

**iii) Investment Table**
```
=====================================================================
   Name          Category       // ...
---------------------------------------------------------------------
APPL Inc          Stock
Dollar          Monetary
[Name]           Futures
...
=====================================================================
```

**iv) Donation Table**
```
=====================================================================
    Unit Name      Amount           Date                  Memo
---------------------------------------------------------------------
BountySource          1         Apr. 9, 2022        Fake donation
Bill Foundation       2         Apr. 9, 2022        Fake donation
...
=====================================================================
```

**v) Degradation Table (Test)**
```
=====================================================================
(Some Name)    Type             //           // ...
---------------------------------------------------------------------
House          debt          -15,000
Credic Card    debt           -6,000
Car            pawn
Watch          pawn
...
=====================================================================
```

**vi) Pivot Table**
```
=====================================================================
(Some Name)
---------------------------------------------------------------------
(To be considered.)
...
=====================================================================
```

### Database
- Firebase in sync
- indexedDB for browser
- SQLite for hand devices
- Parameters in the local storage

### Language
- JavaScript (ES6) for browsers
- Swift for iOS and iPadOS
- Kotlin for Android
- Qt for Windows Phone

## Contributions
Please raise issues or send a pull request.

