# Architecture

The project is split into two applications:

- Angular provides the browser user interface.
- Django provides the REST API, authentication, validation, and persistence.

The applications communicate over HTTP under the `/api/` path. Domain logic belongs in the relevant Django app, while shared backend behavior belongs in `server/apps/common/`.
