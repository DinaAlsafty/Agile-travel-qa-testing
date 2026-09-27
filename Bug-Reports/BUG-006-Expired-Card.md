# BUG-006 – Expired Card Accepted

## Summary

The system allows the user to complete a booking using an expired card expiry date.

## Preconditions

* User is logged in.
* User has selected a flight.
* Required passenger information has been entered.
* User is on the Payment page.

## Steps to Reproduce

1. Proceed to the Payment page.
2. Enter the required payment information.
3. Enter an expiry date that has already passed.
4. Click **Pay/Continue**.

## Actual Result

The system accepts the expired card expiry date and allows the booking to be completed.

## Expected Result

The system should validate the card expiry date and prevent the booking from being completed when an expired card is entered.

## Severity

**High**

## Priority

**High**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
