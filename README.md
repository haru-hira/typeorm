# typeorm
Backend sample implementation for PostgreSQL.
- [TypeORM](https://typeorm.io/#/)
- [TypeScript](https://www.typescriptlang.org/)
- [node-postgres](https://node-postgres.com/)

## Installation

```bash
$ yarn install
```

## Initial Settings
1. Check `ormconfig.json`.  
   Edit following attributes.
   - host: {your database host or 127.0.0.1}
   - port: {your database port}
   - username: '{your username}'
   - password: '{your password}'
1. Create database 'typeorm'.
1. Execute migration.
   ```bash
   $ yarn typeorm migration:generate -n UserMigration
   ```

## Running the app

```bash
$ yarn start
```

## Usage
Request to `http://localhost:3000/{APIs}`.  
Use ex:
[Advanced REST client](https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo/details).

## APIs
Check `src/routes.ts`.
