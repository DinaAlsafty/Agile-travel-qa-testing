# BUG-002 – Past Departure Date Accepted

## Summary

The system allows the user to select a departure date in the past.

## Preconditions

* User is logged in.
* User is on the flight search page.

## Steps to Reproduce

1. Log in to the Agile Travel website.
2. Navigate to the flight search page.
3. Select a valid departure city.
4. Select a valid arrival city.
5. Select a date in the past as the departure date.
6. Select a valid return date.
7. Click **Search/Continue**.

## Actual Result

The system accepts the past departure date and allows the user to continue with the booking flow.

## Expected Result

The system should prevent the user from selecting a past departure date and display an appropriate validation message.

## Severity

**Medium**

## Priority

**Medium**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
