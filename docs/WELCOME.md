<h1 align="center">Express Typescript Service Skeleton</h1>

<p align="center">
  Skeleton for new typescript services based on express
</p>

<p align="center">
    <a href="https://github.com/AlbertHernandez/express-typescript-service-skeleton/actions/workflows/nodejs.yml?branch=main"><img src="https://github.com/AlbertHernandez/express-typescript-service-skeleton/actions/workflows/nodejs.yml/badge.svg?branch=main" alt="nodejs"/></a>
</p>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Installing](#installing)
- [Building](#building)
- [Testing](#testing)
  - [Jest with Testing Library](#jest-with-testing-library)
- [Linting](#linting)

## Installing

```bash
nvm install 18.0.0
nvm use
npm install npm@8.3.0 -g
npm install
```

## Building

```bash
npm run build
```

## Testing

### Jest with Testing Library

```bash
npm run test
```

## Linting

Run the linter

```bash
npm run lint
```

Fix lint issues automatically

```bash
npm run lint:fix
```

# Authentication

We love security!
<SecurityDefinitions />

# Tutorial (displayed in the left navigation)

<PullRight>
This part will appear in the right pane.
</PullRight>

This part is in the body. Lorem ipsum dolor!

# Errors

We follow the error response format proposed in [RFC 7807](https://tools.ietf.org/html/rfc7807)
also known as Problem Details for HTTP APIs. As with our normal API responses,
your client must be prepared to gracefully handle additional members of the response.

## Unauthorized

<RedocResponse pointer={"#/components/responses/Unauthorized"} />

## AccessForbidden

<RedocResponse pointer={"#/components/responses/AccessForbidden"} />
