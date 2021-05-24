# EternalRealmsMC

### See more: https://eternalrealms.net/wiki/public-api/

Usage:
```javascript
const EternalRealmsClient = require('eternalrealmsmc');
const Client = new EternalRealmsClient.Client();
```

Example:

```javascript
const EternalRealmsClient = require('eternalrealmsmc');
const Client = new EternalRealmsClient();

console.log(await Client.online())
```

Result:
```
{
    "survival": [
        {
            "group": 4,
            "name": "Kashall",
            "user_id": 19,
            "start": 1621810191
        }
    ],
    "stage": [],
    "dev": []
}
```