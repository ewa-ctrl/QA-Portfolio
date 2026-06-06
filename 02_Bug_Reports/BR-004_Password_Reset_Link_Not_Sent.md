# BR-004: Passwore Reset Link Not Sent
## Bug ID
BR-004
## Title
Password reset link is not sent to a valid email address
## Severity
High
## Priority
High
## Environment
-Browser: Google Chrome 137

-OS: Windows 11

-Test Environment: QA

## Preconditions
-User account exists in the system
-User knows registered email address
## Steps to Reproduce

1.Open Login page

2.CLick "Forgot Password"

3.Enter a valid registered email address.

4.Click "Send Reset Link"

## Expected Result
System sends password reset email to the registered email address and displays a confirmation message.
## Actual Result
No email is recived and no confirmation message is displayed.
## Frequency
100%
## Status
Open
## Notes
User cannot reset password and regain access to the account

