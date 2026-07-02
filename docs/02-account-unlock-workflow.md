# Account Unlock Workflow

## Scenario

A user cannot log in because their domain account is locked.

## Possible Causes

- Multiple wrong password attempts
- Old password saved on another device
- Outlook or mobile mail app using an old password
- Mapped network drive using old credentials
- VPN login attempts with old credentials

## Helpdesk Steps

1. Verify the user's identity.
2. Find the user account in Active Directory.
3. Check if the account is locked.
4. Unlock the account.
5. Ask the user to try logging in again.
6. If the account locks again, check for saved old credentials.
7. Document the ticket.

## Example Ticket Note

User identity verified. Account was locked due to failed login attempts. Account unlocked and user successfully logged in.
