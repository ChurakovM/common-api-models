# Common API Models

This repository contains shared OpenAPI component definitions used across services.

## Purpose
The goal of this module is to provide reusable schema components (DTOs) for consistent API design between client APIs and backend services. This ensures that all Polyglots services share the same definitions for users, polyglots, locations, and other core entities.

## Structure
- `openapi/common-api-models.yaml` — OpenAPI 3.0.3 file defining common reusable schemas.

## Example usage
In another OpenAPI spec, reference these models:
```yaml
$ref: './../../target/openapi/common-api-models.yaml#/components/schemas/Password"'
