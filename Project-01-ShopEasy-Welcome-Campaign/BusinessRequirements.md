# Business Requirements

## Company

ShopEasy

## Campaign Name

New Customer Welcome Campaign

## Objective

Send welcome emails to newly registered
customers who have provided marketing consent.

## Customer Data Required

- CustomerID
- FirstName
- EmailAddress
- RegistrationDate
- MarketingConsent

## Eligibility Conditions

A customer qualifies when:

1. The registration date matches the campaign date.
2. MarketingConsent is Yes.
3. The customer has a valid email address.

## Expected Results

Eligible customers should receive a welcome email.

Customers without marketing consent should
not receive the marketing email.

## Additional Considerations

- Avoid duplicate welcome emails.
- Respect unsubscribe status.
- Record campaign execution results.
