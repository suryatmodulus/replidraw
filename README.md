# replicache-todo

TodoMVC/React ported to Replicache/Next.js/Postgres.

The simplest possible starter sample for Replicache.
Intended for customers to clone and start editing.

## Status

This is under active development and doesn't work yet.

The mutators and subscriptions are in place but I don't know if they work, haven't tested them yet.

What's left is to basically port https://codesandbox.io/s/react-todomvc-using-hooks-ph7md to modern NextJS/React/TypeScript and hook it up to Replicache. See frontend/link.tsx for first example already done.

## Other TODOs

- Switch to Superstruct
- Add instructions about provisioning Supabase and working locally
- Publish `resolver` or whatever is necessary to not have it in `util`
- Factor out the server into some separate open source repo
