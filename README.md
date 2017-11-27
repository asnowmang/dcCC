#### dcCC
Credit card number validator written in dc

#### About
Currently only works with Amex and Visa. It checks the first two numbers for 34
and 37. If either is true, the card is American Express. If both are false, it
checks if the first number is 4. If true, it's a Visa card. If neither is true
or the card number is >16 or <14 digits it deems the card number invalid.

#### Example
    % dc dcCC.dc
    Enter CC #
    37123456789121
    American Express

#### License
This program is licensed under the ISC License. See LICENSE.md for details.
