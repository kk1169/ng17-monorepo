# CREATE ANGULAR MONOREPO APPLICATION #
```shell
npx create-nx-workspace@latest angular-monorepo --preset=angular-monorepo
nx serve shell
npx nx g @nx/angular:app quiz --directory=apps/quiz --dry-run
nx g @nx/angular:library shared-ui --directory=libs/shared/ui --standalone
nx g @nx/angular:library ui --directory=libs/ui --standalone
nx graph
```
