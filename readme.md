<p align="center">
    <img src="https://camo.githubusercontent.com/c7f49c483a3c5a145ff55c7331520a65e12abff2/68747470733a2f2f692e696d6775722e636f6d2f774434725674342e706e67" width="300"/>
</p>

# awesome-prisma [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


## :tipping_hand_woman: About this List

This is a collection of **awesome resources** about [Prisma](https://www.prisma.io/ "Build a GraphQL server with any database") :heart_eyes:

### :chart_with_upwards_trend: Legend

* :hammer: - hands-on resources, like step-by-step tutorials
* :open_book: - In-depth resources, like detailed articles
* :eyes: - Examples and templates
* :package: - Reusable software packages
* :movie_camera: - Video Tutorial

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
- [:small_red_triangle: Prisma Server Deployment](#small_red_triangle-prisma-server-deployment)
- [:movie_camera: Video tutorials](#movie_camera-video-tutorials)
- [:family_man_woman_girl_boy: Community](#family_man_woman_girl_boy--community)



## :books: General Resources

* :hammer: [How to GraphQL](https://www.howtographql.com/ "The Fullstack Tutorial for GraphQL")
* :eyes: [Reference Example](https://github.com/graphcool/graphql-server-example "GraphQL server example (Airbnb clone) using Prisma, `graphql-yoga` & `prisma-binding`.")
* :eyes: [Example Collection](https://github.com/graphcool/prisma/tree/master/examples "Wide range of generally useful examples.")
* :eyes: [GraphQL Boilerplates](https://github.com/graphql-boilerplates/ "Collection of production-ready GraphQL boilerplate projects.")
* :hammer: [Quickstart](https://www.prismagraphql.com/docs/quickstart/ "The fastest way to get up and running with Prisma, for backend and frontend developers.")
* :open_book: [Reference Documentation](https://www.prismagraphql.com/docs/reference/ "Deep dive into how developing with Prisma works.")
* :hammer: [Tutorials](https://www.prismagraphql.com/docs/tutorials/ "Quick tutorials that walk you through practical examples and demonstrate concrete features of Prisma.")
* :open_book: [What is Prisma](https://www.prismagraphql.com/docs/reference/introduction/what-is-prisma-apohpae9ju)
* :open_book: [Prisma Deep Dive Article](https://divu.in/prisma-deep-dive-3162dea2820c)
* :eyes: [Prisma Shop Example](https://github.com/KATT/shop "Full-stack React/Prisma/TS/GraphQL E-Commerce Example")
* :eyes: [Angular Starter Project](https://github.com/coformatique/prisma-auth0-angular-starter)
* :eyes: [Boilerplate for a Fullstack GraphQL App with React & Prisma](https://github.com/alan345/naperg "Node Apollo Prisma Express React GraphQL")

## :mag: GraphQL Server Development

### GraphQL Yoga

* :package: [GraphQL Yoga](https://github.com/graphcool/graphql-yoga/ "Fully-featured GraphQL Server with focus on easy setup, performance & great developer experience")
* :hammer: [How to build a GraphQL Server with GraphQL Yoga](https://blog.graph.cool/tutorial-how-to-build-a-graphql-server-with-graphql-yoga-6da86f346e68)
* :eyes: [Collection of GraphQL Yoga Examples](https://github.com/graphcool/graphql-yoga/tree/master/examples)

### Server Deployment

* :hammer: [Deploying a GraphQL Server with Apex Up](https://blog.graph.cool/deploying-graphql-servers-with-apex-up-522f2b75a2ac)
* :hammer: [Deploying GraphQL Servers with Zeit Now](https://blog.graph.cool/deploying-graphql-servers-with-zeit-now-85f4757b79a7)
* :eyes: [Apex Up and GraphQL Yoga Example](https://github.com/maxdarque/up-graphql-yoga-server-example "Tutorial on how deploy your graphql-yoga server on AWS Lambda with Apex Up")

### GraphQL Resolvers

* :open_book: [Demystifying the `info` argument in GraphQL Resolvers](https://blog.graph.cool/graphql-server-basics-demystifying-the-info-argument-in-graphql-resolvers-6f26249f613a)
* :open_book: [Different use cases for the `info` argument](https://www.graph.cool/forum/t/querying-specific-fields-in-db-from-local-service-with-prisma/2075/4?u=nilan)
* :eyes: [Collection of common scenarios](https://github.com/graphql-boilerplates/node-graphql-server/issues/35)
* :eyes: [Resolver Forwarding Example](https://github.com/graphcool/prisma/tree/master/examples/resolver-forwarding)
* :eyes: [Subscription Resolver Examples](https://github.com/graphcool/prisma-binding/issues/78)

### GraphQL Bindings

* :open_book: [Composing GraphQL APIs with GraphQL Bindings](https://blog.graph.cool/reusing-composing-graphql-apis-with-graphql-bindings-80a4aa37cff5)
* :package: [Prisma Binding](https://github.com/graphcool/prisma-binding)
* :package: [GraphQL Binding](https://github.com/graphql-binding/graphql-binding)

### Authentication

* :eyes: [Email & Password Authentication Example](https://github.com/graphcool/prisma/tree/master/examples/auth)
* :eyes: [Github Authentication Example](https://github.com/graphcool/prisma/tree/master/examples/github-auth)
* :hammer: [Authentication with Github OAuth2](https://medium.com/@maticzavadlal/graphcool-1-0-example-series-authentication-282f274b8343)
* :eyes: [Facebook Authentication Example](https://github.com/harrisrobin/prisma-facebook-auth-example)
* :eyes: [Auth0 Authentication Boilerplate](https://github.com/coformatique/prisma-auth0-starter)

### Permissions

* :eyes: [Permissions Example](https://github.com/graphcool/prisma/tree/master/examples/permissions)
* :open_book: [GraphQL Directive Permissions](https://blog.graph.cool/graphql-directive-permissions-authorization-made-easy-54c076b5368e)
* :package: [GraphQL Shield](https://github.com/maticzav/graphql-shield)

### Subscriptions

* :eyes: [Subscriptions Example](https://github.com/graphcool/prisma/tree/master/examples/subscriptions)

### File Handling

* :eyes: [File Handling Example](https://github.com/graphcool/prisma/tree/master/examples/file-handling-s3)
* :open_book: [File Handling with AWS S3, Prisma & graphql-yoga](https://manticarodrigo.com/file-handling-s3-prisma-graphql-yoga/)
* :open_book: [Handling files with Amazon S3 and Prisma](https://medium.com/@maticzavadlal/graphcool-1-0-examples-series-file-api-3b16b4b8785f)

### Error Handling

* :open_book: [Handling Errors in GraphQL](https://dev.to/andre/handling-errors-in-graphql--2ea3)

## :small_red_triangle: Prisma Server Deployment

* :hammer: [Local (Docker)](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/local-(docker)-meemaesh3k)
* :hammer: [Digital Ocean (Docker Machine)](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/digital-ocean-(docker-machine)-texoo9aemu)
* :hammer: [Digital Ocean (manual)](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/digital-ocean-(manual)-texoo6aemu)
* :hammer: [Prisma Cloud](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/prisma-cloud-ua9gai4kie)
* :eyes: [Prisma Docker](https://github.com/maxdarque/prisma-docker)
* :eyes: [Prisma Docker Compose](https://github.com/akoenig/prisma-docker-compose/)
* :hammer: [Kubernetes](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/kubernetes-aiqu8ahgha)
* :hammer: [Deployment to AWS EC2](https://www.graph.cool/forum/t/deployment-of-prisma-to-aws-ec2/2880?u=nilan)
* :eyes: [Serverless Template](https://www.graph.cool/forum/t/minimal-serverless-prisma-project-template/2827?u=nilan)
* :hammer: [AWS Fargate](https://blog.graph.cool/how-to-deploy-a-prisma-cluster-to-aws-fargate-using-docker-cloudformation-293aa8727b89)

## :movie_camera: Video tutorials

* :movie_camera: [React Native and Prisma YouTube Tutorial Series](https://www.youtube.com/watch?v=nyE6shIRzxM&list=PLN3n1USn4xlmqhVdKMurNREwtiUpq-SFy "Introduction for an eCommerce app built with React Native and Prisma GraphQL")
* :movie_camera: [Build a ProductHunt GraphQL server with Prisma + GraphQL Yoga](https://www.youtube.com/watch?v=-n30pzgnkW0&list=PLs2PzMqLzi7Xmx44xTLfOBCwCAxVgQvE_  "Overview: Build a ProductHunt GraphQL server with Prisma + GraphQL Yoga")

## :family_man_woman_girl_boy:  Community

- [GitHub](https://github.com/graphcool/prisma/)
- [Website](https://www.prismagraphql.com)
- [Docs](https://www.prismagraphql.com/docs/)
- [Blog](https://blog.graph.cool/)
- [Forum](https://www.graph.cool/forum)
- [Slack](https://slack.graph.cool/)
- [Twitter](https://twitter.com/graphcool)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Catalin Miron has waived all copyright and
related or neighboring rights to this work.
