# azure-functions-template

## How to use

### Setup
Install:

```bash
npm install -g azure-functions-core-tools@core
```

```bash
yarn install
```

### Available scripts

| Script         | Description                                                                            |
| -------------- | -------------------------------------------------------------------------------------- |
| **new**        | Executes func new -l javascript.                                                       |
| **start**      | Compiles typescript sources, funcpacks results and executes func host start.           |
| **debug**      | Compiles typescript sources and executes func host start.                              |
| **az:publish** | Compiles typescript sources, funcpacks results and executes azure functionapp publish. |
| **az:logs**    | Executes func azure functionapp logstream.                                             |
