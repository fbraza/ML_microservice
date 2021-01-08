# From data source to model with Kubernetes

## Rationale

The idea is to build a sequence of data processing logic isolated in distinct containers. The objective here is to delegate the data wrangling task to some Kubernetes `Pod.spec.initContainers`. Once all subsequent tasks are done the model
is ran in `Pod.spec.containers`.

## Installation

## Usage

## Developers

## Personal Notes

- One issue to allow the API to communicate with kaggle (resolution name error)
  - Solved providing cni to the minikube cluster


TEST KEYS ipad
