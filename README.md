# Costrace Documentation

This is the Mintlify-powered documentation for Costrace.

## Local Development

Install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the development server:

```bash
mintlify dev
```

The docs will be available at `http://localhost:3000`.

## Deployment

The docs are automatically deployed to `docs.costrace.dev` via Mintlify's hosting.

To deploy:

1. Push changes to the `main` branch
2. Connect your repository to Mintlify at [mintlify.com](https://mintlify.com)
3. Set the subdomain to `docs.costrace.dev`

## Structure

```
docs/
├── mint.json              # Mintlify configuration
├── introduction.mdx       # Home page
├── quickstart.mdx         # Quick start guide
├── sdks/
│   ├── python.mdx         # Python SDK docs
│   └── nodejs.mdx         # Node.js SDK docs
└── api/
    ├── authentication.mdx # Auth guide
    └── traces.mdx         # Traces API reference
```

## Editing

All documentation is written in MDX (Markdown with JSX components). See [Mintlify's documentation](https://mintlify.com/docs) for component references.
