# Active Directory Troubleshooting Notes

## Common Issues

### User Cannot Log In

Possible causes:

- Wrong password
- Account locked
- Account disabled
- Password expired
- Domain controller unreachable
- Network or DNS issue

### User Cannot Access Shared Folder

Possible causes:

- User is not in the correct security group
- Permission issue
- Network path issue
- Group Policy not updated

### Group Policy Not Applying

Possible causes:

- User or computer is in the wrong OU
- GPO is not linked correctly
- Security filtering issue
- Policy update has not run yet

Useful command:

```cmd
gpupdate /force
```

### Client Cannot Join Domain

Possible causes:

- DNS is not pointing to the Domain Controller
- Wrong domain name
- Network connectivity issue
- Time difference between client and server
- Domain Controller is offline

Useful commands:

```cmd
ipconfig /all
ping DC01
nslookup lab.local
```

## Helpdesk Principle

Start with simple checks first: username, password, account status, network, DNS and group membership.
