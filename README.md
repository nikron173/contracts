# Repository for Protobuf Contracts

This repository contains the Protobuf definitions for various services and utilities.
The contracts are organized into different directories, each representing a specific service or utility. 

## Directory Structure
- `account/`: Contains Protobuf definitions for the account service.
- `pagination/`: Contains Protobuf definitions for pagination utilities.

## Usage
To generate Go code from the Protobuf definitions, use the provided Makefile. The Makefile includes a `gen` target that builds a Docker image and runs it to generate the Go code. 
