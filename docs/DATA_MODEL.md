# Data model

## Proposed fields

Entries need a date, direction, category, amount, currency, and optional note; never store account numbers.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.