# Lunabase

(This is a work in progress)

**Lunabase** *will be* a development platform, similar to Firebase. 

It is intended to provided an opensource application, but will still rely on Opensouce and other technology to work:

- Database: ArangoDB
- Caching: Redis 
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

curl https://raw.githubusercontent.com/mardix/lunabase/master/setup.sh > setup.sh
chmod 755 setup.sh
./setup.sh

```

This will install:

- Boxie
- Redis
- ArangoDB
- Typesense

(This is a work in progress)

---

License: MIT
