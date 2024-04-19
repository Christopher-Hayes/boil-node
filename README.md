```bash
# One-liner: Create repo. Install deps. Open VSCode.
gh repo create --template Christopher-Hayes/boil-node && cd boil-node && yarn && code .
```

## Setup

```bash
gh repo create --template Christopher-Hayes/boil-node
```

```bash
cd boil-node
```

```bash
yarn
```

## Start

Run your code once.

```bash
yarn start
```

## Dev

Your code will rerun when files change.

```bash
yarn dev
```

# boil-node

A template repo for simple Node.js projects.

Primarly focused on prototyping with Node.JS where the tools should not get in the way.

## Goals with this template

I use Node.JS a lot for small internal tools. Typescript is a must-have when working with data, and it's hassle remembering how to set it up each time to use modern JS features. Popular GitHub Node.JS templates try to be too helpful, and slow down dev.

**This template has..**

- `YES` Supports modern JS features
- `YES` Typescript should just work
- `YES` JS is allowed too, typescript is not forced

**This template does not include..**

- `NO` Aggressive linting
- `NO` Git hooks, vscode settings, or other annoying defaults
- `NO` Testing, just building
- `NO` Messing with tsc build config
