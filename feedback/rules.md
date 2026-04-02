# Feedback & Rules for Claude

## Database Setup
- **Never use `defaultdb`** in PostgreSQL setups. Always create a purpose-named database.
- Why: Explicit preference — defaultdb is sloppy and causes confusion across environments.
- Apply: When setting up any app with a managed database, create a dedicated DB first.

## Communication Style
- Be direct and concise. Don't over-explain or summarize what was just done.
- Just do the work. Don't ask permission for every small step.
