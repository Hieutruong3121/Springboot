# demo-springboot
Demo Java Springboot micro-services application on Kubernetes environment.

![](https://img.shields.io/badge/Environment-Kubernetes-blue)
[![](https://img.shields.io/badge/Owner-minhluantran017-darkviolet)](mailto:minhluantran017@gmail.com)

Tags: <mark>DevOps</mark>, <mark>Java</mark>, <mark>microservices</mark>, <mark>Kubernetes</mark>

***PROJECT STATUS:***

- [x] Development
- [x] Building and Packaging
- [x] Deployment
- [ ] Testing

## Getting Started

### Prerequisites

* Docker
* Helm
* kubectl
* A Kubernetes cluster to deploy onto

### Cloning code

The directory structure is as below:
```
(root)
|___artifacts           --->> Store binaries for each steps
|___build               --->> Contains build scripts
|   |___docker
|___deploy              --->> Contains deploy scripts
|   |___docker-compose
|   |___helm
|___lib                 --->> Contains shared libraries
|___src                 --->> Contains source code
|___tests               --->> Contains automation test scripts
|   |___integration
|   |___functional
|   |___performance
|___pom.xml
|___README.md
```

### Creating war file

You should specify the `PRODUCT_RELEASE` and `BUILD_NUMBER` environment variables 
before taking next steps:

`TODO`

### Building the image

Build application Docker image:

`TODO`

Push Docker image to Docker repository:

`TODO`

### Deploying application


`TODO`

### Running test suites

`TODO`

## CI/CD integration

This project is configured for CI/CD on Jenkins and CircleCI.
All configurations are under `.jenkins`/`.circleci` directory.

More CI/CD tools will be added (depends on my freetime).

## Branching

* **master** - *Master branch*
* **dev** - *Dev branch for development and testing*

## Authors

* **Luan Tran** - *Owner*

## License

This project has no license.

But if you decide to fork or get idea from this, feel free to :star: me. Thanks :wink:
