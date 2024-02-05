### school_management

#### Backend - repository

Set env

```sh
mv .env_example .env.local
```

Docker,

```sh
docker compose up
```

Seed db, and generate prisma client

> create a default user

> username : admin , password : 123456

```sh
# if first time
npx prisma db seed

# else
npm run db:migrate-dev
```
