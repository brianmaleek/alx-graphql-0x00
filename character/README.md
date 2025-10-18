## Tasks

### 0. Write a Query to Get a Specific Character by ID

**mandatory**

**Objective**: Learners will write a GraphQL query to retrieve a specific character’s information using their ID.

Use the following [Endpoint](https://rickandmortyapi.com/graphql)

**Instructions**:

- Write a GraphQL query using the `character(id: ID!)` field to fetch the details of a character. Use ids 1, 2, 3, 4
- Include the following fields in your query: `id`, `name`, ` status`, `species`, `type`, `gender`

**Repo**:

- **GitHub repository**: **alx-graphql-0x00**
- **Directory**: **character**
- **File**: [character/README.md](./character/README.md), [character/character-id-1.graphql](./character/character-id-1.graphql), [character/character-id-1-output.json](./character/character-id-1-output.json), [character/character-id-2.graphql](./character/character-id-2.graphql), [character/character-id-2-output.json](./character/character-id-2-output.json), [character/character-id-3.graphql](./character/character-id-3.graphql), [character/character-id-3-output.json](./character/character-id-3-output.json), [character/character-id-4.graphql](./character/character-id-4.graphql), [character/character-id-4-output.json](./character/character-id-4-output.json)

### 1. Write a Query to Get a List of All Characters

**mandatory**

**Objective**: Learners will create a GraphQL query to retrieve a paginated list of all characters.

**Instructions**:

- Write a GraphQL query using the `characters(page: Int)` field to fetch the list of characters. For page 1, 2, 3, 4
- Select the subfields: `id`, `name`, `status`, and `image`.

**Repo**:

**GitHub repository**: **alx-graphql-0x00**
**Directory**: **character**
**File**: [character/README.md](./character/README.md), [character/characters-page-1.graphql](./character/characters-page-1.graphql), [character/characters-page-1-output.json](./character/characters-page-1-output.json), [character/characters-page-2.graphql](./character/characters-page-2.graphql), [character/characters-page-2-output.json](./character/characters-page-2-output.json), [character/characters-page-3.graphql](./character/characters-page-3.graphql), [character/characters-page-3-output.json](./character/characters-page-3-output.json), [character/characters-page-4.graphql](./character/characters-page-4.graphql), [character/characters-page-4-output.json](./character/characters-page-4-output.json)
