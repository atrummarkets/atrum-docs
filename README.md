# Atrum docs

Mintlify documentation for Atrum — a prediction market where position sizes are private.

## Local preview

```bash
npm i -g mint
mint dev
```

Opens on http://localhost:3000.

## Editing

Pages are MDX. Navigation lives in `docs.json`.

## A note on accuracy

Atrum's privacy claims are specific and easy to overstate. Before changing any page under
`concepts/`, read `concepts/privacy-model` — it draws the exact line between what is hidden
and what is not. Statements like "anonymous" or "fully private" are wrong and will be caught
by anyone reading the contracts.
