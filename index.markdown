---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

**Welcome to Go Phings!**

You’ll find here a lightweight library for building command-line applications, a module for easily creating CRUD HTTP endpoints from structs, a struct-to-database mapping tool (similar to an ORM), and much more. See the list below.

## [broccli](https://github.com/go-phings/broccli/)
Simplifies command line interface management. It allows you to define commands complete with arguments and flags, and attach handlers to them. With validation.

## [crud](https://github.com/go-phings/crud/)
Create REST API HTTP endpoint for simple data management just by defining structs and attaching a handler function to HTTP server.

## [crud-ui](https://github.com/go-phings/crud-ui/)
Module that allows you to run a simple administration panel for struct instances stored in the database. The idea is that you define structs, attach ORM and run a simple function.

## [struct-db-postgres](https://github.com/go-phings/struct-db-postgres/)
Map structs to PostgreSQL tables (like ORM).

## [struct-validator](https://github.com/go-phings/struct-validator/)
Use tags to validate struct field values.

## [terminal-ui](https://github.com/go-phings/terminal-ui/)
Designed to simplify output to a terminal window by allowing the specification of panes with static or dynamic content

## [umbrella](https://github.com/go-phings/umbrella/)
Provides a simple authentication mechanism for an HTTP endpoint. With it, you can wrap any endpoint that should have its access restricted. In addition, it provides additional its own handler for registering new user, activating it and, naturally, signing in and out
