<div align='center'>
  	<img width="500" src="logo.svg" alt="awesome-lint">
  <br>
  <a href='https://awesome.re'>
	  <img src='https://awesome.re/badge.svg' alt='Awesome'>
  </a>
  <p>This is a collection of awesome resources about <a href='https://www.prisma.io/' title='Build a GraphQL server with any database'>Prisma</a></p>
</div>

[Prisma](https://www.prisma.io/ 'Build a GraphQL server with any database') is a performant open-source GraphQL ORM-like layer doing the heavy lifting in your GraphQL server. It turns your database into a GraphQL API which can be consumed by your resolvers via GraphQL bindings.

- :hammer: - Hands-on resources, like step-by-step tutorials
- :open_book: - In-depth resources, like detailed articles
- :eyes: - Examples and templates
- :package: - Reusable software packages
- :movie_camera: - Video tutorial

## Contents

- [:books: General Resources](#books-general-resources)
- [:mag: GraphQL Server Development](#mag-graphql-server-development)
  - [GraphQL Yoga](#graphql-yoga)
  - [Server Deployment](#server-deployment)
  - [GraphQL Resolvers](#graphql-resolvers)
  - [GraphQL Bindings](#graphql-bindings)
  - [Authentication](#authentication)
  - [Permissions](#permissions)
  - [Subscriptions](#subscriptions)
  - [File Handling](#file-handling)
  - [Error Handling](#error-handling)
  - [Multi-tenancy](#multi-tenancy)
- [:small_red_triangle: Prisma Server Deployment](#small_red_triangle-prisma-server-deployment)
- [:movie_camera: Video tutorials](#movie_camera-video-tutorials)
- [:family_man_woman_girl_boy: Community](#family_man_woman_girl_boy-community)

## :books: General Resources

- :hammer: [How to GraphQL](https://www.howtographql.com/ 'The Fullstack Tutorial for GraphQL')
- :eyes: [Reference Example](https://github.com/graphcool/graphql-server-example 'GraphQL server example (Airbnb clone) using Prisma, `graphql-yoga` & `prisma-binding`.')
- :eyes: [Example Collection](https://github.com/prisma/prisma-examples 'Wide range of generally useful examples.')
- :eyes: [GraphQL Boilerplates](https://github.com/graphql-boilerplates/ 'Collection of production-ready GraphQL boilerplate projects.')
- :hammer: [Quickstart](https://www.prisma.io/docs/get-started/01-setting-up-prisma-demo-server-JAVASCRIPT-a001/ 'The fastest way to get up and running with Prisma, for backend and frontend developers.')
- :hammer: [Tutorials](https://www.prisma.io/tutorials/ 'Step-by-step tutorials and articles to help people get the most out of the Prisma ecosystem.')
- :open_book: [What is Prisma](https://www.prisma.io/docs/understand-prisma/prisma-introduction-what-why-how-j9ff/#what-is-prisma)
- :open_book: [Prisma Deep Dive Article](https://divu.in/prisma-deep-dive-3162dea2820c)
- :eyes: [Prisma Shop Example](https://github.com/KATT/shop 'Full-stack React/Prisma/TS/GraphQL E-Commerce Example')
- :eyes: [Boilerplate for a Fullstack GraphQL App with React & Prisma](https://github.com/alan345/naperg 'Node Apollo Prisma Express React GraphQL')
- :eyes: [NestJS - Prisma - Apollo 2](https://github.com/awesome-graphql-space/server-nestjs 'Bootstrap your Nestjs Prisma app within seconds')
- :eyes: [Graphql Microservice Starter](https://github.com/berstend/graphql-microservice-starter 'Nextgen backend stack using independent GraphQL services')
- :package: [RAN-PRISMA : React . GraphQL . Next.js . Prisma Toolkit](https://github.com/mshameer/ran-with-prisma 'RAN-PRISMA : React . GraphQL . Next.js . Prisma Toolkit')
- :open_book: [Prisma Docs Translated into Chinese](https://prisma.1wire.com/)
- :eyes: [Fullstack Boilerplate using React Apollo Prisma Typescript](https://github.com/DylanMerigaud/react-prisma-typescript-fullstack)

## :mag: GraphQL Server Development

### GraphQL Yoga

- :package: [GraphQL Yoga](https://github.com/prisma/graphql-yoga 'Fully-featured GraphQL Server with focus on easy setup, performance & great developer experience')
- :hammer: [Build a GraphQL Server with Prisma and graphql-yoga](https://www.prisma.io/docs/get-started/03-build-graphql-servers-with-prisma-TYPESCRIPT-t201/)
- :eyes: [Collection of GraphQL Yoga Examples](https://github.com/prisma/graphql-yoga/tree/master/examples)

### Server Deployment

- :hammer: [Deploying a GraphQL Server with Apex Up](https://www.prisma.io/tutorials/deploy-a-graphql-server-with-apex-up-cs05/)
- :hammer: [Deploying GraphQL Servers with Zeit Now](https://www.prisma.io/tutorials/deploy-a-graphql-server-with-zeit-now-cs04/)
- :eyes: [Apex Up and GraphQL Yoga Example](https://github.com/maxdarque/up-graphql-yoga-server-example 'Tutorial on how deploy your graphql-yoga server on AWS Lambda with Apex Up')
- :open_book: [Prisma Horizontal Scaling](https://techblog.commercetools.com/prisma-horizontal-scaling-a-practical-guide-3a05833d4fc3 'Prisma Horizontal Scaling: a practical guide')

### GraphQL Resolvers

- :open_book: [Demystifying the `info` argument in GraphQL Resolvers](https://www.prisma.io/blog/graphql-server-basics-demystifying-the-info-argument-in-graphql-resolvers-6f26249f613a/)
- :open_book: [Different use cases for the `info` argument](https://www.prisma.io/forum/t/querying-specific-fields-in-db-from-local-service-with-prisma/2075/4)
- :eyes: [Collection of common scenarios](https://github.com/graphql-boilerplates/node-graphql-server/issues/35)
- :eyes: [Subscription Resolver Examples](https://github.com/prisma/prisma-binding/issues/78)
- :open_book::hammer: [GraphQL Mutation Arguments Validation with Yup using graphql-middleware](https://medium.com/@jonathancardoso/graphql-mutation-arguments-validation-with-yup-using-graphql-middleware-645822fb748)

### GraphQL Bindings

- :open_book: [Composing GraphQL APIs with GraphQL Bindings](https://www.prisma.io/blog/reusing-and-composing-graphql-apis-with-graphql-bindings-80a4aa37cff5/)
- :package: [Prisma Binding](https://github.com/prisma/prisma-binding)
- :package: [GraphQL Binding](https://github.com/graphql-binding/graphql-binding)

### Authentication

- :eyes: [Email & Password Authentication Example](https://github.com/prisma/prisma-examples/tree/master/node/graphql-auth)
- :hammer: [Authentication with GitHub OAuth2](https://medium.com/@maticzavadlal/graphcool-1-0-example-series-authentication-282f274b8343)
- :eyes: [Facebook Authentication Example](https://github.com/harrisrobin/prisma-facebook-auth-example)

### Permissions

- :open_book: [GraphQL Directive Permissions](https://www.prisma.io/blog/graphql-directive-permissions-authorization-made-easy-54c076b5368e/)
- :package: [GraphQL Shield](https://github.com/maticzav/graphql-shield)

### Subscriptions

- :eyes: [Subscriptions Example](https://github.com/prisma/prisma-examples/tree/master/node/graphql-subscriptions)

### File Handling

- :open_book: [File Handling with AWS S3, Prisma & graphql-yoga](https://www.prisma.io/forum/t/graphql-file-handling-with-aws-s3-prisma-graphql-yoga/2779)
- :open_book: [Handling files with Amazon S3 and Prisma](https://medium.com/@maticzavadlal/graphcool-1-0-examples-series-file-api-3b16b4b8785f)

### Error Handling

- :open_book: [Handling Errors in GraphQL](https://dev.to/andre/handling-errors-in-graphql--2ea3)

### Multi-tenancy

- :hammer: [Building a multi-tenant application with Prisma](https://medium.zenika.com/building-a-multi-tenant-application-with-prisma-11bf890304d6)
- :package: [prisma-multi-tenant](https://github.com/Errorname/prisma-multi-tenant)

## :small_red_triangle: Prisma Server Deployment

- :hammer: [Local (Docker)](<https://www.prismagraphql.com/docs/tutorials/cluster-deployment/local-(docker)-meemaesh3k>)
- :hammer: [Digital Ocean (Docker Machine)](https://www.prisma.io/tutorials/deploy-prisma-to-digitalocean-with-docker-machine-ct06)
- :hammer: [Digital Ocean (manual)](https://www.prisma.io/tutorials/deploy-prisma-to-digitalocean-ct12/)
- :eyes: [Prisma Docker](https://github.com/maxdarque/prisma-docker)
- :eyes: [Prisma Docker Compose](https://github.com/akoenig/prisma-docker-compose/)
- :hammer: [Kubernetes](https://www.prisma.io/tutorials/deploy-prisma-to-kubernetes-ct13/)
- :hammer: [Deployment to AWS EC2](https://www.graph.cool/forum/t/deployment-of-prisma-to-aws-ec2/2880?u=nilan)
- :eyes: [Serverless Template](https://www.graph.cool/forum/t/minimal-serverless-prisma-project-template/2827?u=nilan)
- :hammer: [AWS Fargate](https://www.prisma.io/tutorials/deploy-prisma-to-aws-fargate-ct14/)

## :movie_camera: Video tutorials

- :movie_camera: [React Native and Prisma YouTube Tutorial Series](https://www.youtube.com/watch?v=nyE6shIRzxM&list=PLN3n1USn4xlmqhVdKMurNREwtiUpq-SFy 'Introduction for an eCommerce app built with React Native and Prisma GraphQL')
- :movie_camera: [Build a ProductHunt GraphQL server with Prisma + GraphQL Yoga](https://www.youtube.com/watch?v=-n30pzgnkW0&list=PLs2PzMqLzi7Xmx44xTLfOBCwCAxVgQvE* 'Overview: Build a ProductHunt GraphQL server with Prisma + GraphQL Yoga')

## :family_man_woman_girl_boy: Community

- [GitHub](https://github.com/prisma/prisma)
- [Website](https://www.prisma.io)
- [Docs](https://www.prisma.io/docs/)
- [Tutorials](https://www.prisma.io/tutorials)
- [Blog](https://www.prisma.io/blog/)
- [Forum](https://www.prisma.io/forum/)
- [Slack](https://slack.prisma.io/)
- [Twitter](https://twitter.com/prisma)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Catalin Miron has waived all copyright and
related or neighboring rights to this work.
