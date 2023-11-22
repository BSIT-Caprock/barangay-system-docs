# Application Structure

The project mostly follows the default [Laravel 10.x application structure](https://laravel.com/docs/10.x/structure).

## Attributes

Path: `app/Attributes`

Contains traits that are used in models. May include accessors, mutators, relationships, and local scopes for the specified attribute in the trait name.

## Casts

Path: `app/Casts`

Contains custom Eloquent casts classes that define how attributes are cast when retrieved or stored in the database.

## Filament

Path: `app/Filament`

Contains resources and components for the Filament admin panel.

Subdirectories:

- `Actions` - Contains custom Filament actions.
- `Resources` - Contains Filament resources and components for the Filament admin panel.

## Helpers

Path: `app/Helpers`

Contains helper functions.

## Models

Path: `app/Models`

Contains Eloquent model classes representing database tables.

## Observers

Path: `app/Observers`

Contains model observers.

## Policies

Path: `app/Policies`

Contains model policies.

## Providers

Path: `app/Providers`

Classes:

- `AppServiceProvider` - used for other application services.
- `EventServiceProvider` - used to register model events and observers.
- `GlobalScopeServiceProvider` - used to apply global scopes on models.

## Scopes

Path: `app/Scopes`

Contains global scopes for models.

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

## Filament Feature Tests

Path: `tests/Feature/Filament`

Subdirectories:

- `Actions` - for custom action tests
- `Pages` - for common page tests
- `Resources` - for resource-specific tests

<!-- ### API Tests

Path: `tests/Feature/Api`

Contains API tests. -->

## Unit Tests

Path: `tests/Unit`

Contains unit tests, which test generic PHP code used in the project.
