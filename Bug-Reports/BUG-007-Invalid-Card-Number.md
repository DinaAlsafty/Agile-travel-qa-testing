# BUG-007 – Invalid Card Number Accepted

## Summary

The system accepts an invalid card number and allows the booking to be completed.

## Preconditions

* User is logged in.
* User has selected a flight.
* Required passenger information has been entered.
* User is on the Payment page.

## Steps to Reproduce

1. Proceed to the Payment page.
2. Enter a valid card holder's name.
3. Enter `123` in the **Card Number** field.
4. Enter the required expiry information.
5. Click **Pay/Continue**.

## Actual Result

The system accepts the invalid card number and allows the booking to be completed.

## Expected Result

The system should validate the card number format and prevent the booking from being completed when an invalid card number is entered.

## Severity

**High**

## Priority

**High**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
