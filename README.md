# OpenID Connect Single Sign-On

## Your own OpenID Connect (OIDC) Provider in NestJS using node oidc-provider library.

## Start

```bash
$ npm run start:dev
```

OR

```bash
$ yarn start:dev
```

## Example auth request

[?client_id=test\
 &response_type=code\
 &redirect_uri=http://localhost:3001/callback\
 &scope=openid+email
](http://localhost:3001/oidc/auth?client_id=test&response_type=code&redirect_uri=http://localhost:3001/callback&scope=openid+email)
