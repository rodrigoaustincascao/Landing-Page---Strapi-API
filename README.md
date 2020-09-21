# Landing Page with Strapi API

### 📦 Install

```
$ git clone https://github.com/rodrigoaustincascao/Landing-Page---Strapi-API.git

$ yarn install
```

### 🔨 How to use

Pull the latest images

```bash
docker-compose pull
```

Run the stack

```bash
docker-compose up -d
```
## Import the Original date
In the bash postegres

```bash
psql -h 127.0.0.1 -U strapi -d strapi -W < strapi.sql
```

## For dump
In the bash postegres

```bash
pg_dump -c --if-exists --exclude-table=strapi_administrator -h 127.0.0.1 -U strapi -d strapi -W > dump_strapi.sql
```

