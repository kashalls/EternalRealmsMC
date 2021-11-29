# EternalRealmsMC

## This is an wrapper to easily access the public api of Eternal Realms

### Each IP is allowed 100 requests per minute

### See more: <https://eternalrealms.net/wiki/public-api/>

Usage:

```javascript
const EternalRealmsClient = require('eternalrealmsmc');
const Client = new EternalRealmsClient();

console.log(await Client.online())
```

Available Functions:

```
Client.online(server_name/null)
Client.user(username/user_id/uuid)
Client.staff()
Client.stats()
Client.servers()
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
