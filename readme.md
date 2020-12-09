# Lunabase-server

Lunabase-server is the server install for Lunabase.


(This is a work in progress)

**Lunabase** *will be* a development platform, similar to Firebase. 

It is intended to provided an opensource application, but will still rely on Opensouce and other technology to work:

- Document Store: ArangoDB
- Key/Value Store: Redis 
- Search: Typesense
- Storage: AWS S3
- Authentication: Firebase

---

## Setup

#### 1. Get a VPS / Server

For Lunabase to properly work, get a fresh VPS from either Digital Ocean, Linode or any server that will allow you to **SSH** in.

We recommend *Ubuntu 18.04 LTS* as OS

#### 2. Download Lunabase setup.sh

Copy the code below that will download and install **Lunabase**

```sh

curl https://raw.githubusercontent.com/mardix/lunabase-server/master/setup.sh > lunabase-server-setup.sh
chmod 755 lunabase-server-setup.sh
./lunabase-server-setup.sh

```

This will install:

- Boxie
- Redis
- ArangoDB
- Typesense

(This is a work in progress)

#### 3. Setup Cron Backup

---

License: MIT
