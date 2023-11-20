# Directory Structure

## Introduction

The structure of the project follows the default [Laravel 10.x application structure](https://laravel.com/docs/10.x/structure). 

## Casts

Path: `app/Casts`

Contains custom Eloquent casts classes that define how attributes are cast when retrieved or stored in the database.

## Filament

Path: `app/Filament`

Contains resources and components for the Filament admin panel.

Subdirectories: 

- **Actions** - Contains custom filament actions.
- **Resources** - Contains Filament resources and components for the Filament admin panel.

## Models

Path: `app/Models`

Contains Eloquent model classes representing database tables.

Subdirectories: 

- **Listeners** - Contains traits which [register closures](https://laravel.com/docs/10.x/eloquent#events-using-closures) that execute when various model events are dispatched. 
- **Relationships** - Contains traits which define [relationships](https://laravel.com/docs/10.x/eloquent-relationships) and provide associated attributes, [local scopes](https://laravel.com/docs/10.x/eloquent#local-scopes), and methods to models.
- **Scopes** - Contains [global scopes](https://laravel.com/docs/10.x/eloquent#global-scopes).

## Data

Path: `database/data`

Contains data files used as seed data during database seeding.

## Factories

Path: `database/factories`

Contains factory classes used to create records with random data.

## Migrations

Path: `database/migrations`

Contains database migration files that define the structure of database tables and their relationships.

## Seeders

Path: `database/seeders`

Contains seeder classes responsible for populating the database with initial data.

## Feature Tests

Path: `tests/Feature`

Contains feature tests, which run only within the application context.

## Unit Tests

Path: `tests/Unit`

Contains unit tests, which test application-independent pieces of code, such as general computer algorithms. 
