# Random things i need to remember

- How to handle migrations with drizzle-orm and cloudflare D1 SQLite database:
  - npm script:
  ```bash
  bunx drizzle-kit generate && bunx drizzle-kit push && bunx wrangler d1 migrations apply db-name --remote
  ```
