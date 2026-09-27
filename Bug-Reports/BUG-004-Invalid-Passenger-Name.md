# BUG-004 – Invalid Passenger Name Characters Accepted

## Summary

The First Name and Last Name fields accept numeric and special-character values.

## Preconditions

* User is logged in.
* User has selected a flight.
* User is on the Passenger Information page.

## Steps to Reproduce

1. Select a flight and proceed to the Passenger Information page.
2. Enter `123456` in the **First Name** field.
3. Enter `@@@###` in the **Last Name** field.
4. Complete the other required information.
5. Click **Continue**.

## Actual Result

The system accepts numeric and special-character values in the First Name and Last Name fields and allows the user to continue.

## Expected Result

The name fields should validate the entered data and reject values containing invalid numeric or special characters.

## Severity

**Medium**

## Priority

**Medium**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
