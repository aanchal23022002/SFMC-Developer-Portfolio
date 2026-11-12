# Welcome Campaign Test Scenarios

## Test Case 1

Scenario:
Customer registered today with marketing consent.

Expected Result:
Customer is eligible for the welcome email.

## Test Case 2

Scenario:
Customer registered today without marketing consent.

Expected Result:
Customer must not receive the marketing email.

## Test Case 3

Scenario:
Customer registered yesterday.

Expected Result:
Customer is not eligible for today's new-registration campaign.

## Test Case 4

Scenario:
Customer has already received the welcome email.

Expected Result:
Customer must not receive a duplicate welcome email.

## Test Case 5

Scenario:
Customer email address is missing.

Expected Result:
Customer must not be selected for the email send.

## Testing Status

Test cases documented.

Actual SFMC execution has not yet been performed.
