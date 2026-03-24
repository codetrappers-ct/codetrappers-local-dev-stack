# Coetrappers Local Dev Stack

`coetrappers-local-dev-stack` is a local development stack for the Coetrappers project set.
Docker-based local environment for WordPress development.
The codebase is scaffolded to be a clean starting point, not a complete production feature.

## Project Summary

- Slug: `coetrappers-local-dev-stack`
- Type: Local development stack
- Focus: docker, local, dev

## What This Repository Includes

- Docker Compose services for WordPress and MariaDB
- Volume mapping for `wp-content` development
- Environment example file for local setup

## Recommended Project Structure

- `docker-compose.yml`: local WordPress stack
- `.env.example`: compose project defaults

## Setup

- Copy `.env.example` to `.env` if you want custom compose settings.
- Run `docker compose up -d`.
- Mount plugins or themes into `wp-content` for local development.

## How To Extend It

- Use this repository as a starting point rather than a finished production implementation.
- Adapt the structure to the hosting, release, and team conventions you expect to use.
- Document any project-specific conventions as the repository evolves.

## Development Notes

- The generated code favors readability and a low-friction starting structure.
- Credentials, provider integrations, persistence rules, and deployment concerns still need to be implemented for real use.
- Review capability checks, sanitization, and data storage choices before using any starter in production.

## Roadmap

- Add Xdebug, Mailpit, or search services as needed.
- Create onboarding scripts for new developers.
- Align local images with staging or production requirements.
