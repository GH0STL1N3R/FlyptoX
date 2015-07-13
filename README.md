# FlyptoX

> Pithy project description

## Team

  - __Product Owner__: Michael Symmes
  - __Scrum Master__: Dick Treichel
  - __Development Team Members__: Simon Burns, Amy Li, Mokhtar Naamani, Michael Symmes, Dick Treichel

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> Some usage instructions

## Requirements

- Node 0.10.x
- Redis 2.6.x
- Postgresql 9.1.x
- etc
- etc

## Development

### Installing Dependencies

From within the root directory:

```sh
sudo npm install -g bower
sudo npm install -g knex
npm install
bower install
```

### Database setup

Create a database using `createdb` tool

    createdb flyptox

Enter `psql` command shell. Create a role and grant access to the database

    create role flyptox with login;
    grant all privileges on database flyptox to flyptox;

exit psql

Run knex migrations

    knex migrate:latest

### Roadmap

View the project roadmap [here](LINK_TO_PROJECT_ISSUES)


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
