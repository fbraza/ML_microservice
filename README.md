# From data source to model: an example of pipeline using kubernetes

## Rationale

The idea is to build a sequence of data processing logic isolated in distinct containers. The objective here is to
delegate the data wrangling task to some kubernetes `initContainers`. Once all subsequent taks are done the model
is ran in a "normal" containers.

## Installation

## Usage

## Developers

## Personal Notes

- One issue to allow the API to communicate with kaggle (resolution name error)
  - Solved providing cni to the minikube cluster
