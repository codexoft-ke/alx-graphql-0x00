# Character by ID Queries

This folder contains GraphQL queries to fetch a specific character by ID from the Rick and Morty GraphQL API, along with the captured outputs for IDs 1–4.

Endpoint: https://rickandmortyapi.com/graphql

Fields requested: id, name, status, species, type, gender

How to run (optional):
- Use any GraphQL client or curl to POST the query.
- Replace the `id` in the query or variables as needed.

---

# Characters list (paginated)

Queries to fetch lists of characters using `characters(page: Int)` with required fields `id, name, status, image` for pages 1–4. See files:
- characters-page-1.graphql + characters-page-1-output.json
- characters-page-2.graphql + characters-page-2-output.json
- characters-page-3.graphql + characters-page-3-output.json
- characters-page-4.graphql + characters-page-4-output.json
