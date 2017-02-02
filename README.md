# SitePen TSLint Rules

A collection of TSLint rules used on SitePen projects

## Linting Files

### `tslint.json`

These are the standard linting rules we use on TypeScript projects

### `tslint-dojo1.json`

These rules are used when writing Dojo 1 projects in TypeScript

## Usage

TSLint has a great reference for creating [Sharable Configuration and Rules](https://palantir.github.io/tslint/2016/03/31/sharable-configurations-rules.html)

Here's a quick start:

```
npm install tslint tslint-sitepen --save-dev
```

create a `tslint.json` file that extends from `tslint-sitepen` and add your own rules

```json
{
    "extends": "tslint-sitepen",
    "rules": {
        "no-addition": true
    }
}
```

