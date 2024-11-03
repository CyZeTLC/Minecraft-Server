
# Minecraft-Server Whitelist-Mangement

A simple project that ensures that whitelist management on a Minecraft server works simply. 




## Authors

- [@cyzetlc](https://www.github.com/CyZeTLC)


## Features

- Viewing the players on the whitelist
- Add/remove players from the whitelist
- Exact player data of all players on the whitelist


## Installation

You need to upload the webinterface onto your webspace & put the plugin into your spigot/bukkit plugins folder. 

After the web interface has been uploaded and the plugin has been packed into the folder, the same database must be set in both configs. 
```json
  {
    "mysql": {
        "hostname": "127.0.0.1",
        "port": 3306,
        "database": "database_name",
        "username": "database_login",
        "password": "database_password",
        "poolSize": 3
    }
  }
```

