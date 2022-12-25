[<img src="https://assets.arc.codes/architect-logo-500b@2x.png" width=500>](https://github.com/architect/plugins)

## Architect plugins

> A collection of plugins for the [OpenJS Architect](https://arc.codes) framework


### Plugins maintained by Architect

- [TypeScript](https://www.npmjs.com/package/@architect/plugin-typescript) - TypeScript runtime support with realtime Lambda transpiling + sourcemaps
- [External `@tables`](https://www.npmjs.com/package/@architect/plugin-external-tables) - Enable access to external DynamoDB tables from other Architect projects, legacy Architect projects, and non-Architect projects
- [Sandbox Lambda invoker](https://www.npmjs.com/package/@architect/plugin-lambda-invoker) - Interactively invoke Lambdas in Sandbox with arbitrary events
- [Node.js prune](https://www.npmjs.com/package/@architect/plugin-node-prune) - Clean excess `node_modules` cruft from your project during deployment
- [Budget watch](https://www.npmjs.com/package/@architect/plugin-budget-watch) - Monitor app spend and stop Lambdas when the limit is reached
- [Storage private](https://www.npmjs.com/package/@architect/plugin-storage-private) - Define any number of arbitrary private S3 buckets for your application
- [Storage public](https://www.npmjs.com/package/@architect/plugin-storage-public) - Define any number of arbitrary public S3 buckets for your application
- [API Gateway `REST` API](https://www.npmjs.com/package/@architect/plugin-rest-api) - Support for legacy API Gateway `REST` APIs
- [Remix](https://www.npmjs.com/package/@architect/plugin-remix) - Deploy a Remix app to AWS Lambda and S3 with support for `remix watch` built into Sandbox.


### Plugins maintained by the community

> Note: community plugins are not officially supported, endorsed, or closely vetted by Architect maintainers. As with any code from vendors unknown to you, reviewing such plugins before adding them to your project is advisable.

- [Lambda X-Ray Tracing](https://www.npmjs.com/package/arc-plugin-add-xray) - Enable AWS X-Ray Tracing for all, some, or select Lambdas.
- [Lambda ENV Variables](https://www.npmjs.com/package/arc-plugin-lambda-env) - Get faster access to the physical names of Architect-created resources via Lambda environment variables
- [Image transformer](https://www.npmjs.com/package/@ryanbethel/arc-image-plugin) - Drop large images into the static folder of an Architect app and request a transformed version
- [Remove local routes](https://www.npmjs.com/package/herschel666-arc-macros-remove-local-routes) - Remove select routes prior to deployment; handy when you're leveraging HTTP handlers for local scaffolding tasks
- [Custom log groups](https://www.npmjs.com/package/herschel666-arc-macros-custom-log-groups) - Create log groups for with a custom log retention interval
- [API Gateway CORS](https://www.npmjs.com/package/@copper/macro-apig-cors) - Manage CORS headers automatically
- [JWT auth](https://www.npmjs.com/package/arc-macro-jwt) - Leverage API Gateway built-in HTTP API JWT authorizers
- [Override CloudFormation values](https://www.npmjs.com/package/@yodata/arc-macro-set-cf-value) - Set and override CloudFormation values upon deployment
- [Site URL](https://www.npmjs.com/package/arc-macro-site-url) - Allow Lambdas to discover the site's URL via an SSM parameter
- [TailwindCSS](https://www.npmjs.com/package/arc-plugin-tailwindcss) - Enables TailwindCSS workflow - runs JIT CLI watcher with Sandbox, builds minified CSS prior to deployment
- [Named routes](https://www.npmjs.com/package/arc-plugin-named-routes) - Easier web routing by adding names to HTTP routes in `app.arc`, then use the helper function to refer to them by name
- [arc-plugin-esbuild](https://www.npmjs.com/package/arc-plugin-esbuild) - Bundle your functions with esbuild
- [arc-plugin-multi-region](https://www.npmjs.com/package/@ticketplushq/arc-plugin-multi-region) - Allows to deploy Architect projects on multi regions using Global Tables
- [arc-plugin-s3rver](https://www.npmjs.com/package/@ticketplushq/arc-plugin-s3rver) - This plugin runs an s3 server (thanks to s3rver) in the architect sandbox
