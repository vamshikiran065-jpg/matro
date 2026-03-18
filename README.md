<p align="center">
  <img src="./assets/logo.png" width="200" />
</p>

<p align="center">
  <b>Matro</b> is a GraphQL code generator inspired by Swagger.
</p>

<p align="center">
  <a href="https://github.com/firstcontributions/matro/actions/">
    <img alt="CI Status" src="https://img.shields.io/github/actions/workflow/status/firstcontributions/matro/ci.yml" />
  </a>
  <a href="https://github.com/firstcontributions/matro/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/firstcontributions/matro" />
  </a>
  <a href="https://github.com/firstcontributions/matro/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/firstcontributions/matro" />
  </a>
  <a href="https://codeclimate.com/github/firstcontributions/matro/maintainability">
    <img alt="Maintainability" src="https://api.codeclimate.com/v1/badges/99dfc661e165766b7528/maintainability" />
  </a>
  <a href="https://codeclimate.com/github/firstcontributions/matro/test_coverage">
    <img alt="Coverage" src="https://api.codeclimate.com/v1/badges/99dfc661e165766b7528/test_coverage" />
  </a>
</p>

---

## Overview

Matro is a tool designed to generate GraphQL schemas and related backend components, inspired by the simplicity and efficiency of Swagger. It aims to streamline backend development by automating repetitive tasks.

---

## Getting Started

### 1. Prerequisites

* Go 1.17+
* gRPC dependencies:

  * `google.golang.org/grpc v1.44.0`
  * `google.golang.org/protobuf v1.27.1`
* GNU Make

---

### 2. Installation

```bash id="s1d9e2"
git clone https://github.com/firstcontributions/matro.git
cd matro
make config
make build
```

---

## Features / Progress

* [x] GraphQL schema generator
* [x] gRPC protobuf and service stub generator
* [x] gRPC service implementation
* [x] Models / store generator
* [x] GraphQL Golang implementation
* [ ] React Relay generator

---

## Project Structure

```text id="y7f8k1"
cmd/        → CLI entry points  
pkg/        → Core logic  
internal/   → Internal modules  
```

---

## Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## License

This project is licensed under the MIT License.


 
