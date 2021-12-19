# PROJECT_NAME

## Get Started

1. To create a project based on this template click on the `Use this template` button
2. Find and Replace `PROJECT_NAME` placeholder with the real project name
3. Delete libraries which do not satisfy project needs
4. Delete this section from `README`
5. To cover your tracks and incorporate the changes to the project's `Initial commit`, run these commands:

```sh
git commit -a --amend
git push -f origin master
```

---

## Documentation

Project is based on `Nest.js`, a progressive Node.js framework for building efficient, reliable and scalable server-side applications. Check out the [documentation](https://docs.nestjs.com/) for more information.

## Prerequisites

- `node`
- `npm`
- `@nestjs/cli` (optional)

## Usage

**Firstly, install all necessary dependencies:**

```sh
npm install
```

**To start server:**

```sh
npm start
```

**To run your tests:**

```sh
npm run test
```

## Folder structure

```
template-nest/
├── dist (compiled code)
└── src
│   ├── guards (auth)
│   └── modules (each module and his module, service, resolver etc.)
└── test (basic e2e tests)
```

## What's Inside

- Node.js Framework

  - [Nest.js](https://nestjs.com/)

- Type-checking

  - [TypeScript](https://www.typescriptlang.org/docs/home.html)

- Code quality tools

  - [Prettier](https://prettier.io/)
  - [ESLint](https://eslint.org/)

- Other
  - [Sentry](https://sentry.io/welcome/)
  - [Jest](https://jestjs.io/)
