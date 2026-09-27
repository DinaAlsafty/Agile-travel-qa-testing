# BUG-003 – Return Date Earlier Than Departure Date Accepted

## Summary

The system allows the user to select a return date that is earlier than the departure date.

## Preconditions

* User is logged in.
* User is on the flight search page.

## Steps to Reproduce

1. Log in to the Agile Travel website.
2. Navigate to the flight search page.
3. Select a valid departure city.
4. Select a valid arrival city.
5. Select a valid departure date.
6. Select a return date that is earlier than the departure date.
7. Click **Search/Continue**.

## Actual Result

The system accepts the return date even though it is earlier than the departure date and allows the user to continue.

## Expected Result

The system should prevent the user from selecting a return date earlier than the departure date and display an appropriate validation message.

## Severity

**Medium**

## Priority

**High**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
