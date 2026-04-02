---
name: Never use defaultdb in PostgreSQL
description: Always create a named database — never use the default "defaultdb" for any app
type: feedback
---

Never use `defaultdb` in PostgreSQL setups.
**Why:** User explicitly does not want it used — always create a purpose-named database.
**How to apply:** When setting up any app with a DO managed database, create a dedicated database before connecting the app.
