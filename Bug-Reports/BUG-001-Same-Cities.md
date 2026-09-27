# BUG-001 – Same Departure and Arrival City Accepted

## Summary

The system allows the user to select the same city as both the departure and arrival city.

## Preconditions

* User is logged in.
* User is on the flight search page.

## Steps to Reproduce

1. Log in to the Agile Travel website.
2. Navigate to the flight search page.
3. Select the same city in the **From** and **To** fields.
4. Enter valid departure and return dates.
5. Click **Search/Continue**.

## Actual Result

The system accepts the same city as both departure and arrival and allows the user to continue with the booking flow.

## Expected Result

The system should prevent the user from selecting the same city for both departure and arrival, or display an appropriate validation message.

## Severity

**Medium**

## Priority

**Medium**

## Testing Type

**Exploratory Testing**

## Environment

* Browser: Google Chrome
* Application: Agile Travel
