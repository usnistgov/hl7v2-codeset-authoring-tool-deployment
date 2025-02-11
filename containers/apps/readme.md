# Environment Configuration

To set up the environment for the application, create a `.env` file in the appropriate folder based on the environment needs. Use `containers/apps/prod/env` for production and `containers/apps/dev/env` for development. This file will contain the necessary environment variables required for the application to run.

## Steps to Create the `.env` File

1. Navigate to the appropriate folder:
    - For production: `containers/apps/prod/env`
    - For development: `containers/apps/dev/env`
2. Create a new file named `.env`.
3. Add the required environment variables to the `.env` file.

## Example of a `.env` File

Below is an example of what the `.env` file might look like:

```plaintext
# Database configuration
CODESET_AUTHORING_TOOL_PORT=9000
POSTGRES_USER=postgres-user
POSTGRES_PASSWORD=postgres-password
POSTGRES_DB=example-db
POSTGRES_URL=jdbc:postgresql://example-db-url:5432/example-db
ADMIN_USER_PASSWORD=admin-password
JWT_SECRET=jwt-secret
```

Make sure to replace the placeholder values with the actual values for your environment.

## Important Notes

- Ensure that the `.env` file is not committed to version control to avoid exposing sensitive information.

