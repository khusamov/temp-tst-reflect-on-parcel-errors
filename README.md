# temp-tst-reflect-on-parcel-errors

Start
-----

```
yarn
yarn start
```

Error:

```
parcel-transformer-ttypescript: Debug Failure.

  Error: Debug Failure.
  at /Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/typescript/lib/typescript.js:19675:89
  at String.replace (<anonymous>)
  at formatStringFromArgs
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/typescript/lib/typescript.js:19675:21)
  at Object.createCompilerDiagnostic
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/typescript/lib/typescript.js:19789:20)
  at tryReadFile
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/typescript/lib/typescript.js:40090:40)
  at Object.readConfigFile
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/typescript/lib/typescript.js:40055:32)
  at getConfigReflectionSection
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/tst-reflect-transformer/dist/config.js:11:23)
  at readConfig
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/tst-reflect-transformer/dist/config.js:27:24)
  at createConfig
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/tst-reflect-transformer/dist/config.js:51:20)
  at Activator.prepareConfig
  (/Users/khusamov/Documents/repo/github.com/khusamov/temp-tst-reflect-on-parcel-errors/node_modules/tst-reflect-transformer/dist/contexts/TransformerContext.js:51:50)

```