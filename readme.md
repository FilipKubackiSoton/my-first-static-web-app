# Vanilla JavaScript App

[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview) allows you to easily build JavaScript apps in minutes. Use this repo with the [quickstart](https://docs.microsoft.com/azure/static-web-apps/getting-started?tabs=vanilla-javascript) to build and customize a new static site.

This repo is used as a starter for a _very basic_ HTML web application using no front-end frameworks.

This repo has a dev container. This means if you open it inside a [GitHub Codespace](https://github.com/features/codespaces), or using [VS Code with the remote containers extension](https://code.visualstudio.com/docs/remote/containers), it will be opened inside a container with all the dependencies already installed.

// {
//   "$schema": "https://dataapibuilder.azureedge.net/schemas/v0.5.34/dab.draft.schema.json",
//   "data-source": {
//     "database-type": "mssql",
//     "options": {
//       "set-session-context": false
//     },
//     "connection-string": ""
//   },
//   "runtime": {
//     "rest": {
//       "enabled": true,
//       "path": "/rest"
//     },
//     "graphql": {
//       "allow-introspection": true,
//       "enabled": true,
//       "path": "/graphql"
//     },
//     "host": {
//       "mode": "production",
//       "cors": {
//         "origins": [],
//         "allow-credentials": false
//       },
//       "authentication": {
//         "provider": "StaticWebApps"
//       }
//     }
//   },
//   "entities": {}
// }