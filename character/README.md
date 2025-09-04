# GraphQL Character Query Task

## Objective

The goal of this task is to write a GraphQL query to retrieve a specific character’s information using their **ID**.  
You will practice querying GraphQL APIs and extracting specific fields from the response.

---

## Instructions

1. Use the provided GraphQL **endpoint**.
2. Write a query using the `character(id: ID!)` field.
3. Fetch the following fields for each character:
   - `id`
   - `name`
   - `status`
   - `species`
   - `type`
   - `gender`
4. Run queries for characters with IDs **1, 2, 3, and 4**.
5. Save your queries and responses as files in the **character** directory.

---

## Files to Include

Inside the `character` directory, the following files must be present:

- `README.md` → This file (task documentation).
- `character-id-1.graphql` → Query for character with ID `1`.
- `character-id-1-output.json` → JSON response for ID `1`.
- `character-id-2.graphql` → Query for character with ID `2`.
- `character-id-2-output.json` → JSON response for ID `2`.
- `character-id-3.graphql` → Query for character with ID `3`.
- `character-id-3-output.json` → JSON response for ID `3`.
- `character-id-4.graphql` → Query for character with ID `4`.
- `character-id-4-output.json` → JSON response for ID `4`.

---

## Example Query

```graphql
query GetCharacter {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
```
