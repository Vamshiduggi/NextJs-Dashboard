## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Database seeding

Set `POSTGRES_URL` and a long, random `SEED_SECRET` in your environment (including
Vercel Production). Seed the database by sending a `POST` request to `/seed` with
`Authorization: Bearer <SEED_SECRET>`. The endpoint returns `401` if the token
does not match and `503` if `SEED_SECRET` is not configured. Do not commit the
secret.
