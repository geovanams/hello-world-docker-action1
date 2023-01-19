# hello-world-docker-action1

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

[![.github/workflows/main.yml](https://github.com/geovanams/hello-world-docker-action1/actions/workflows/main.yml/badge.svg)](https://github.com/geovanams/hello-world-docker-action1/actions/workflows/main.yml)

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the Octocat'
