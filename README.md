# Epistula


Epistula is an open-source project written in golang to check whether an email is valid or not.

## How does it work?

Epistula follows the following techniques :

### Syntax validation

This check verifies that the email address has the correct format, including the correct characters for the username and domain, as well as the correct number of @ symbols, periods, and other special characters.

### Domain validation: 

This check verifies that the domain of the email address exists and is registered.

### SMTP validation 

This check uses the Simple Mail Transfer Protocol (SMTP) to send a test message to the email address and checks for a successful delivery.

### Email pattern validation 

This check verifies that the email address is not a disposable email address, which are often used for temporary or throwaway email addresses.

There are several patterns that email validation services use to detect disposable email addresses **(DEA)**, also known as temporary or throwaway email addresses. Here are a few examples:

- **Domain-based pattern**: This pattern checks if the email address uses a domain that is known to be associated with disposable email addresses. For example, email addresses that use domains such as "mailinator.com", "guerrillamail.com", or "temp-mail.org" are likely to be disposable email addresses.

- **Recency-based pattern**: This pattern checks if the email address was recently created. Disposable email addresses are often created on-the-fly and are not used for very long, so email addresses that are less than a certain age (e.g. a week old) are more likely to be disposable.

- **Character-based pattern**: This pattern checks if the email address has certain characteristics that are commonly associated with disposable email addresses. For example, email addresses that have a large number of random characters or that use numbers as placeholders are more likely to be disposable.

- **Email pattern validation**: This pattern check verifies that the email address is not a disposable email address, which are often used for temporary or throwaway email addresses.

These patterns are not foolproof and that some legitimate email addresses may be incorrectly flagged as disposable email addresses. Additionally, the disposable email providers are always changing and the list of domains can change over time.
