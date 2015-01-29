# Listserv Admin Commands

## Approving new members
```
To: lyris@infolist.nws.noaa.gov
Body:
login [password]
member approve [#####] [#####]
```

## Review listserv membership
This returns a list of email addresses
```
To: lyris@infolist.nws.noaa.gov
Body:
login [password]
review noaa-ed-network
```

## Report listserv statistics
```
To: lyris@infolist.nws.noaa.gov
Body:
login [password]
report noaa-ed-network
```

## Delete member
This unsubscribes an email from the list
```
To: lyris@infolist.nws.noaa.gov
Body:
login [password]
delete noaa-ed-network [email] quiet
```
