# Vendored-in librairies

## log.c

A very simple lib for handling logs in C is available at

  https://github.com/rxi/log.c

It says that

  log.c and log.h should be dropped into an existing project and compiled
  along with it.

So this directory contains a _vendored-in_ copy of the log.c repository.

## SubCommands.c

The single-header library is used to implement parsing "modern" command lines.

## JSON

The parson librairy at https://github.com/kgabis/parson is a single C file
and MIT licenced. It allows parsing from and serializing to JSON.

## pg

We vendor-in some code from the Postgres project at
https://git.postgresql.org/gitweb/?p=postgresql.git;a=summary. This code is
licenced under The PostgreSQL Licence, a derivative of the BSD licence.
