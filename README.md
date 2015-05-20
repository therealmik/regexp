# regexp
Regular Expressions (Strict matches only)

Some languages require double-backslashes to encode a single one, please adjust accordingly.

Anchors included - this will match exactly one of the item in question.

## base64
```regexp
^([A-Za-z0-9+/]{4})*([A-Za-z0-9+/]{4}|[A-Za-z0-9+/]{2}[AEIMQUYcgkosw048]=|[A-Za-z0-9+/][AQgw]==)?$
```

## IP address
```regexp
^(25[0-5]|2[0-4][0-9]|1[0-9][0-9]|[1-9]?[0-9])(\.((25[0-5]|2[0-4][0-9]|1[0-9][0-9]|[1-9]?[0-9]))){3}$
```
