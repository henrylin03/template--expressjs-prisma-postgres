# Template
This is a template for me to quickly spin-up a full-stack, TypeScript, web app using:
- ExpressJS _(to be added)_
- Prisma ORM with PostgreSQL integration
- EJS templating _(to be added)_

## Setup
Ensure that PostgreSQL database has already been created. Inside of the `.env` file in the root of this repository, ensure to have:
```.env
DATABASE_URL="postgresql://<username>:<password>@<localhost:5432>/<db-name>?schema=public"
```