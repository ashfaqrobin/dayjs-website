---
id: converting-to-zone
title: Converting to Zone
---

Change the time zone and update the offset and return a Day.js object instance.

@>Timezone
```javascript
dayjs.extend(utc)
dayjs.extend(timezone)
dayjs("2013-11-18 11:55").tz("America/Toronto")
dayjs("2013-11-18 11:55").tz("America/Toronto", true)
```

On passing a second parameter as true, only the timezone (and offset) is updated, keeping the local time same. 
