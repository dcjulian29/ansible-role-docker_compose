# Ansible Role: docker_compose

[![Lint](https://github.com/dcjulian29/ansible-role-docker_compose/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-docker_compose/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-docker_compose.svg)](https://github.com/dcjulian29/ansible-role-docker_compose/issues)

This an Ansible role to install Docker Compose and related utilities to manage services

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.docker_compose
  src: https://github.com/dcjulian29/ansible-role-docker_compose.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
