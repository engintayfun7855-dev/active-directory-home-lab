# Basic Group Policy Notes

## What is Group Policy?

Group Policy allows administrators to manage settings for users and computers in a Windows domain environment.

## Common Examples

- Password policy
- Account lockout policy
- Drive mapping
- Printer deployment
- Desktop restrictions
- Control Panel restrictions
- Software restrictions

## Useful Command

```cmd
gpupdate /force
```

## Helpdesk Relevance

Helpdesk technicians often troubleshoot issues caused by Group Policy, such as missing mapped drives, printer mapping problems, login restrictions or password policy rules.

## Troubleshooting Checks

1. Is the user or computer in the correct OU?
2. Is the GPO linked to the correct OU?
3. Is security filtering configured correctly?
4. Has the client received the latest policy?
5. Run `gpupdate /force` and test again.
