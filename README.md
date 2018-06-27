# microservicios-netflixoss
#
## Overview

This repo contains many microservices projects

### Build
Use this way to build the entire project without tests

```bash
$ mvn clean compile package -Dmaven.test.skip=true
```
### Installation
- install jenkins url: http://200.107.241.6:8080
- install postgresql postgresql-contrib
- install sonarqube-6.7.4 http://200.107.241.6:9000

### Changelog
All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog and this project adheres to Semantic Versioning.
### [Unreleased]

### [1.0.0] - 2018-06-26
### Changed
- microservice-demo-order/src/main/java/com/ewolff/microservice/order/OrderApp.java
```bash
System.out.println(“Added by me in OrderApp ”);
```
- microservice-demo-customer/src/main/java/com/ewolff/microservice/custo
mer/CustomerApp.java
```bash
System.out.println(“Added by me in CustomerApp ”);
```
- microservice-demo-catalog/src/main/java/com/ewolff/microservice/catalog/Item.java
```bash
System.out.println(“Added by me in Item ”);
```
## [0.0.2] - 2018-06-23
### Added
- Explanation of the recommended reverse chronological release ordering.
### 0.0.1 - 2018-06-22
### Added
- It starts by fork the repository: https://github.com/richyyjd/microservicios-netflixoss
### .
