# Password Reset Workflow

## Scenario

A user reports that they cannot log in because they forgot their password.

## Helpdesk Steps

1. Verify the user's identity.
2. Locate the user account in Active Directory.
3. Check if the account is locked.
4. Reset the user's password.
5. Enable "User must change password at next logon".
6. Ask the user to log in with the temporary password.
7. Confirm that the user can access the system.
8. Document the ticket.

## Example Ticket Note

User identity verified. Account was locked due to multiple failed login attempts. Account unlocked and temporary password assigned. User successfully logged in and changed password.

## Security Note

Password reset should never be performed without identity verification.
