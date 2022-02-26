# Changelog

## [[0.1.0]](https://github.com/boyuai/nestjs-oauth2-server/compare/0.0.4...0.1.0) - 26/02/2022

### Changed

- BREAKING: You don't have to register this module in `app.module.ts` anymore.
- BREAKING: `@OAuth2Model` is deprecated in favor of `@Injectable`, meanwhile you should use `modelClass` to specify a model service for oauth2-server. Now you can inject database repository in oauth model service.

## [[0.0.4]](https://github.com/boyuai/nestjs-oauth2-server/compare/0.0.3...0.0.4) - 25/11/2020

### Changed

-   update dev dependencies:
    -   typescript to v4
    -   typescript-eslint monorepo to v4
    -   release-it to v14
    -   ts-jest to v26
    -   jest to v26
    -   eslint to v7
    -   renovate to v23.86.1
    -   @types/jest to v26
    -   nest monorepo to v7.5.5
    -   commitlint monorepo to v11
    -   rxjs to v6.6.3
    -   eslint-config-prettier to v6.15.0
    -   prettier to v2.2.0
    -   lint-staged to v10.5.2
    -   eslint-plugin-import to v2.22.1
