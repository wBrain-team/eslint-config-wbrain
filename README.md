# Wbrain ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @wbrain/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@wbrain/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @wbrain/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@wbrain/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @wbrain/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@wbrain/eslint-config/node"
}
```
