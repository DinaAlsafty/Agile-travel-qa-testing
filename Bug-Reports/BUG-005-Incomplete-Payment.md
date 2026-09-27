# BUG-005 – Booking Completed with Incomplete Payment Information

## Summary

The system allows the user to complete a booking without providing all required payment information.

## Preconditions

* User is logged in.
* User has selected a flight.
* Required passenger information has been entered.
* User is on the Payment page.

## Steps to Reproduce

1. Proceed to the Payment page.
2. Enter a value in the **Card Holder's Name** field.
3. Leave the remaining payment fields empty.
4. Click **Pay/Continue**.

## Actual Result

The system accepts the incomplete payment information and displays a booking confirmation page with a booking number.

## Expected Result

The system should validate all required payment fields and prevent the booking from being completed until the required payment information is provided.

## Severity

**High**

## Priority

**High**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
