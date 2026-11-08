# HAVOZA Railway preparation

Use a dedicated HAVOZA Railway project and PostgreSQL service, isolated from KOFAD and CHALIN03.

Required service environment: `DATABASE_URL`, a fresh strong `SESSION_SECRET`, and `APP_ORIGIN` set to the HTTPS origin.

Before production: install and lock dependencies; run Prisma validation, migrations, TypeScript check, tests and full build; implement email verification and rate limiting; test authentication, seller listings, independent moderation and public search; rehearse backup/restore. Do not enable public registration until the missing safeguards are in place.

This is deployment preparation, not a deployed or production-ready release.
