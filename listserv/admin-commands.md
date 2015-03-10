# Listserv Commands

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
## Members unsubscribe themselves
Send a blank email 
```
To: leave-460991-37655.46fc36d015c5a2faa909440dbb3c354a@infolist.nws.noaa.gov 
```
