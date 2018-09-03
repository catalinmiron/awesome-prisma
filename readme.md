# Awesome Prisma [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A collection of awesome things regarding Prisma ecosystem.


## Contents

- [General Resources](#books-general-resources)
- [GraphQL Server Development](#mag-graphql-server-development)
    - [GraphQL Yoga](#graphql-yoga)
    - [Server Deployment](#server-deployment)
    - [GraphQL Resolvers](#graphql-resolvers)
    - [GraphQL Bindings](#graphql-bindings)
    - [Authentication](#authentication)
    - [Permissions](#permissions)
    - [Subscriptions](#subscriptions)
    - [File Handling](#file-handling)
    - [Error Handling](#error-handling)
- [Prisma Server Deployment](#small_red_triangle-prisma-server-deployment)
- [Video Tutorials](#movie_camera-video-tutorials)
- [Community](#family_man_woman_girl_boy--community)



## :books: General Resources

* [How to GraphQL](https://www.howtographql.com/ "The Fullstack Tutorial for GraphQL")
* [Reference Example](https://github.com/graphcool/graphql-server-example "GraphQL server example (Airbnb clone) using Prisma, `graphql-yoga` & `prisma-binding`.")
* [Example Collection](https://github.com/graphcool/prisma/tree/master/examples "Wide range of generally useful examples.")
* [GraphQL Boilerplates](https://github.com/graphql-boilerplates/ "Collection of production-ready GraphQL boilerplate projects.")
* [Quickstart](https://www.prismagraphql.com/docs/quickstart/ "The fastest way to get up and running with Prisma, for backend and frontend developers.")
* [Reference Documentation](https://www.prismagraphql.com/docs/reference/ "Deep dive into how developing with Prisma works.")
* [Tutorials](https://www.prismagraphql.com/docs/tutorials/ "Quick tutorials that walk you through practical examples and demonstrate concrete features of Prisma.")
* [What is Prisma](https://www.prismagraphql.com/docs/reference/introduction/what-is-prisma-apohpae9ju)
* [Prisma Deep Dive Article](https://divu.in/prisma-deep-dive-3162dea2820c)
* [Prisma Shop Example](https://github.com/KATT/shop "Full-stack React/Prisma/TS/GraphQL E-Commerce Example ")
* [Angular Starter Project](https://github.com/coformatique/prisma-auth0-angular-starter)

## :mag: GraphQL Server Development

### GraphQL Yoga

* [GraphQL Yoga](https://github.com/graphcool/graphql-yoga/ "Fully-featured GraphQL Server with focus on easy setup, performance & great developer experience")
* [How to build a GraphQL Server with GraphQL Yoga](https://blog.graph.cool/tutorial-how-to-build-a-graphql-server-with-graphql-yoga-6da86f346e68)
* [Collection of GraphQL Yoga Examples](https://github.com/graphcool/graphql-yoga/tree/master/examples)

### Server Deployment

* [Deploying a GraphQL Server with Apex Up](https://blog.graph.cool/deploying-graphql-servers-with-apex-up-522f2b75a2ac)
* [Deploying GraphQL Servers with Zeit Now](https://blog.graph.cool/deploying-graphql-servers-with-zeit-now-85f4757b79a7)
* [Apex Up and GraphQL Yoga Example](https://github.com/maxdarque/up-graphql-yoga-server-example "Tutorial on how deploy your graphql-yoga server on AWS Lambda with Apex Up")

### GraphQL Resolvers

* [Demystifying the `info` argument in GraphQL Resolvers](https://blog.graph.cool/graphql-server-basics-demystifying-the-info-argument-in-graphql-resolvers-6f26249f613a)
* [Different use cases for the `info` argument](https://www.graph.cool/forum/t/querying-specific-fields-in-db-from-local-service-with-prisma/2075/4?u=nilan)
* [Collection of common scenarios](https://github.com/graphql-boilerplates/node-graphql-server/issues/35)
* [Resolver Forwarding Example](https://github.com/graphcool/prisma/tree/master/examples/resolver-forwarding)
* [Subscription Resolver Examples](https://github.com/graphcool/prisma-binding/issues/78)

### GraphQL Bindings

* [Composing GraphQL APIs with GraphQL Bindings](https://blog.graph.cool/reusing-composing-graphql-apis-with-graphql-bindings-80a4aa37cff5)
* [Prisma Binding](https://github.com/graphcool/prisma-binding)
* [GraphQL Binding](https://github.com/graphql-binding/graphql-binding)

### Authentication

* [Email & Password Authentication Example](https://github.com/graphcool/prisma/tree/master/examples/auth)
* [Github Authentication Example](https://github.com/graphcool/prisma/tree/master/examples/github-auth)
* [Authentication with Github OAuth2](https://medium.com/@maticzavadlal/graphcool-1-0-example-series-authentication-282f274b8343)
* [Facebook Authentication Example](https://github.com/harrisrobin/prisma-facebook-auth-example)
* [Auth0 Authentication Boilerplate](https://github.com/coformatique/prisma-auth0-starter)

### Permissions

* [Permissions Example](https://github.com/graphcool/prisma/tree/master/examples/permissions)
* [GraphQL Directive Permissions](https://blog.graph.cool/graphql-directive-permissions-authorization-made-easy-54c076b5368e)
* [GraphQL Shield](https://github.com/maticzav/graphql-shield)

### Subscriptions

* [Subscriptions Example](https://github.com/graphcool/prisma/tree/master/examples/subscriptions)

### File Handling

* [File Handling Example](https://github.com/graphcool/prisma/tree/master/examples/file-handling-s3)
* [File Handling with AWS S3, Prisma & graphql-yoga](https://manticarodrigo.com/file-handling-s3-prisma-graphql-yoga/)
* [Handling files with Amazon S3 and Prisma](https://medium.com/@maticzavadlal/graphcool-1-0-examples-series-file-api-3b16b4b8785f)

### Error Handling

* [Handling Errors in GraphQL](https://dev.to/andre/handling-errors-in-graphql--2ea3)

## :small_red_triangle: Prisma Server Deployment

* [Local (Docker)](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/local-(docker)-meemaesh3k)
* [Digital Ocean (Docker Machine)](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/digital-ocean-(docker-machine)-texoo9aemu)
* [Digital Ocean (manual)](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/digital-ocean-(manual)-texoo6aemu)
* [Prisma Cloud](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/prisma-cloud-ua9gai4kie)
* [Prisma Docker](https://github.com/maxdarque/prisma-docker)
* [Prisma Docker Compose](https://github.com/akoenig/prisma-docker-compose/)
* [Kubernetes](https://www.prismagraphql.com/docs/tutorials/cluster-deployment/kubernetes-aiqu8ahgha)
* [Deployment to AWS EC2](https://www.graph.cool/forum/t/deployment-of-prisma-to-aws-ec2/2880?u=nilan)
* [Serverless Template](https://www.graph.cool/forum/t/minimal-serverless-prisma-project-template/2827?u=nilan)
* [AWS Fargate](https://blog.graph.cool/how-to-deploy-a-prisma-cluster-to-aws-fargate-using-docker-cloudformation-293aa8727b89)

## :movie_camera: Video tutorials
* [React Native and Prisma YouTube Tutorial Series](https://www.youtube.com/watch?v=nyE6shIRzxM&list=PLN3n1USn4xlmqhVdKMurNREwtiUpq-SFy "Introduction for an eCommerce app built with React Native and Prisma GraphQL")
* [Build a ProductHunt GraphQL server with Prisma + GraphQL Yoga](https://www.youtube.com/watch?v=-n30pzgnkW0&list=PLs2PzMqLzi7Xmx44xTLfOBCwCAxVgQvE_)

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
