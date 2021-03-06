[SOFTSPIDERS](https://github.com/softspiders/softspiders)

# lerna

Starter for [Lerna](https://lerna.js.org/) monorepo

---

## Feature tags

- lerna
- starter
- template

## Children
- [React application starter with library in Lerna monorepo](https://github.com/softspiders/lerna-react-lib-starter)
- [Minimalistic template for NextJS application with library in Lerna monorepo](https://github.com/softspiders/lerna-next-with-lib)
- [Minimalistic CRA in TypeScript with UiLib and Storybook in Lerna](https://github.com/softspiders/cra-ts-uilib-storybook-lerna)
- [Minimalistic CRA in TypeScript with UiLib, Storybook and Storyshots in Lerna](https://github.com/softspiders/cra-ts-uilib-storybook-storyshots-lerna)
- [Minimalistic React app in TypeScript with UiLib and Storybook in Lerna and building war by Maven](https://github.com/softspiders/cra-ts-uilib-storybook-lerna-mvn-war)
- [Minimalistic JS library development environment on Lerna](https://github.com/softspiders/lerna-lib-app-starter)
- [+ ***publishing***,***versioning***: lerna-version-publish-starter](https://github.com/softspiders/lerna-version-publish-starter)

---
## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin)

---

## Lerna installation

```
npm install --global lerna
```
---

## Install

Being at the root, execute

```
npm run bootstrap
```

---

## Run

Run simplest *some-command* which was previously defined in *scripts* field of *package.json* files.

```
npm run some-command
```

See the result:

```
lerna notice cli v3.20.1
lerna info Executing command in 2 packages: "npm run some-command"
lerna info run Ran npm script 'some-command' in 'package-1' in 0.7s:

> package-1@0.1.0 some-command D:\tmp\200102\lerna\packages\package-1
> echo some-command for package-1

some-command for package-1
lerna info run Ran npm script 'some-command' in 'package-2' in 0.7s:

> package-2@0.1.0 some-command D:\tmp\200102\lerna\packages\package-2
> echo some-command for package-2

some-command for package-2
lerna success run Ran npm script 'some-command' in 2 packages in 0.7s:
lerna success - package-1
lerna success - package-2

```
---

### License

Licensed under the [MIT license](./LICENSE). 

