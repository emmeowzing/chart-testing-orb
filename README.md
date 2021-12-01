Helm `chart-testing` orb for CircleCI
-------------------------------------

This orb provides a set of commands and jobs for [`chart-testing`](https://github.com/helm/chart-testing) in CircleCI workflows. Commands include 

### Usage

### Development

This orb has been developed in *unpacked* form. You may view its packed source with
```shell
$ circleci orb pack src/
```
#### `pre-commit`

This repository uses `pre-commit` to uphold certain code styling and standards. You may install the hooks listed in [`.pre-commit-config`](.pre-commit-config) with
```shell
$ pre-commit install
```