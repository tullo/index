# TOC

- [Angular](#sngular)
- [AuthN & AuthZ](#authn--authz)
- [CI/CD](#cicd)
- [Cloud](#cloud)
- [Go Projects](#go-projects)
- [IaC](#iac---infrastructure-as-code)
- [Next.js](#nextjs)
- [Tooling](#tooling)

## Angular
[Angular Mini Book, with Angular 15 and Spring Boot 3.0](https://github.com/mraible/angular-book/releases)

##  AuthN & AuthZ

| Repo | Meta |
|---|---|
| [fusionauth](https://github.com/tullo/fusionauth) | User authn & authz using FusionAuth for secure access management |

## CI/CD

| Repo | Meta |
|---|---|
| [cicd-cloudapp](https://github.com/tullo/cicd-cloudapp) | CI/CD pipeline with github actions. Builds docker image, pushes image to Jfrog registry, deploys to kubernetes cluster using Helm chart |
| [fly-app](https://github.com/tullo/flyapp-deploy-on-push) | CI/CD to Fly platform with github actions using buildpacks |

## Cloud
| Repo | Meta |
|---|---|
| [podspec](https://github.com/tullo/podspec) | Good defaults for the most common Kubernetes workloads. Adds security and uptime features |


## Go Projects
| Repo | Meta |
|---|---|
| [bun-realworld-app](https://github.com/tullo/bun-realworld-app) | Uses: `Bun Router`, `Bun DB`, `bun/migrate`, `bun/dbfixture` provided by [Bun Go ORM](https://bun.uptrace.dev/). Implements the realworld JSON API as specified in the [spec](https://github.com/gothinkster/realworld) |
| [conf](https://github.com/tullo/conf) | Provides support for using environment variables and command line arguments for configuration |
| [crdb](https://github.com/tullo/crdb) | CockroachDB for local dev using Go database drivers, Go ORM libs, crdb testserver package, migrations tests, crdb docker containers |
| [dgraph-godoc-alice](https://github.com/tullo/dgraph-godoc-alice) | Dgraph [godoc](https://pkg.go.dev/github.com/dgraph-io/dgo/v2@v2.2.0) example usage of the Dgraph Go client API v200.03.0 (gRPC) |
| [dgraph-travel](https://github.com/tullo/dgraph-travel) | Baseline for building graph database apps using [Dgraph](https://dgraph.io/) GraphQL |
| [invoice-mvp](https://github.com/tullo/invoice-mvp) | Invoice REST [Level-3: HyperMedia/HATEOAS](https://devopedia.org/richardson-maturity-model) API, HAL [(Hypertext Application Language)](https://stateless.group/hal_specification.html) documents, use cases with [hexagonal architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html), or ports & adapters architecture, user authn & authz with IDP service and JWT, HTTP response caching |
| [microservice](https://github.com/tullo/microservice) | Add `.proto` file. Scaffold Go code. Implement gRPC service. Done. (Drone CI, Elastic APM) |
| [otel-workshop](https://github.com/tullo/otel-workshop) | OpenTelemetry instrumentation of code for tracing and metrics collection using different exporters: Aspecto, Datadog, Elastic, Honeycomb, Instana, Lightstep, LogicMonitor, New Relic, SigNoz, Sentry, Splunk, Sumo Logic, Uptrace |
| [proxercise](https://github.com/tullo/proxercise/tree/main/go) | Examples, Exercises, Quizzes, Go cheat-sheet, Useful Terminal Control Sequences |
| [search](https://github.com/tullo/search) | Simple frontend to the sales-api service |
| [service](https://github.com/tullo/service) | Go service starter kit is a starting point for building production grade scalable web service applications |
| [shippy](https://github.com/tullo/shippy) | microservice, protobuf, grpc-go, Bootstrap4, MongoDB, PostgreSQL,, Reactjs |
| [short](https://github.com/tullo/short) | A short-link server Go application, powered by CockroachDB |
| [snptx](https://github.com/tullo/snptx) | Go web application (argon2id, embed, pgx, migrate, pat, middleware, sessions, dockertest) |
| [wikifeedia](https://github.com/tullo/wikifeedia) | CockroachDB [Follower Reads](https://www.cockroachlabs.com/docs/stable/topology-follower-reads.html), server and crawler Go applications, webapp uses [React](https://reactjs.org/) and [Apollo](https://www.apollographql.com/) GraphQL |
| [wild-workouts-go-ddd](https://github.com/tullo/wild-workouts-go-ddd-example) | DDD, Clean Architecture, CQRS |

## IaC - Infrastructure as Code

- [Terraform](https://github.com/tullo/learning/tree/main/terraform)

## Next.js

| Repo | Meta |
|---|---|
| [keystone-sickfits](https://github.com/tullo/keystone-sickfits) | Frontend (React, Apollo Client, Next.js), Backend (Keystone.js, Node, MongoDB) |
| [nextjs-blog-theme](https://github.com/tullo/nextjs-blog-theme) | Next.js, Tailwind blog template, using markdown, dark & light themes |


## Tooling

| Repo | Meta |
|---|---|
| [age](https://github.com/FiloSottile/age) | Secure file encryption tool, format, and Go library  |
| [benchstat](https://cs.opensource.google/go/x/perf) | Computes statistical summaries and A/B comparisons of Go benchmarks |
| [errcheck](https://github.com/kisielk/errcheck) | checking for unchecked errors in go programs |
| [gofumpt](https://github.com/mvdan/gofumpt) | Enforce a stricter format than `gofmt` |
| [hey](https://github.com/rakyll/hey) | Sends some load to a web application |
| [kind](https://github.com/kubernetes-sigs/kind) | Kubernetes IN Docker |
| [ko](https://github.com/google/ko) | Build and deploy Go applications on kubernetes |
| [kubeval](https://github.com/instrumenta/kubeval) | Validates Kubernetes configuration files |
| [kustomize](https://github.com/kubernetes-sigs/kustomize) | Customization of Kubernetes YAML configurations |
| [kustomize-sops](https://github.com/viaduct-ai/kustomize-sops) | Kustomize Plugin for SOPS Encrypted Resources |
| [mailhog](https://github.com/mailhog/MailHog) | Email testing tool for developers |
| [mkcert](https://github.com/FiloSottile/mkcert) | Generate locally-trusted development certificates |
| [oapi-codegen](https://github.com/deepmap/oapi-codegen) | OpenAPI v3 client and server code generator |
| [postman](https://www.postman.com/downloads/) | Testing APIs |
| [protobuf-go](https://github.com/protocolbuffers/protobuf-go) | Go support for Protocol Buffers |
| [protoc](https://github.com/protocolbuffers/protobuf/releases) | Protocol Buffer compiler |
| [protoc-gen-go-grpc](https://grpc.io/docs/languages/go/quickstart/) | gRPC Go plugin - generates client and server interfaces |
| [sops](https://github.com/mozilla/sops) | Secrets OPerationS - tool for managing secrets |
| [staticcheck](https://staticcheck.io/docs/running-staticcheck/cli/) | Advanced Go linter |
| [structlayout](https://github.com/dominikh/go-tools/tree/master/cmd/structlayout) | Prints the layout of a struct - byte offset and size of each field, respecting alignment/padding |

[^^^^](#toc)
