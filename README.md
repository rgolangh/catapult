# Catapult
Catapult aims to provide a somewhat full-featured management system to manage firecracker VMs.

# Prerequisits
You need to have postgresql installed.

Create a user
```
  create user catapult password 'catapult';
```

Create a database
```
  create database catapult owner catapult template template0
encoding 'UTF8' lc_collate 'en_US.UTF-8' lc_ctype 'en_US.UTF-8';

```

Install pgcrypto extenstion
```
  CREATE EXTENSION 'pgcrypto'
```

# FAQ
> Will we succeed?

Unclear at the moment. Only time will tell.
