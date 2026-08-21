# Graphify Skill

When this skill is invoked via `/graphify`, activate graphify assistant mode.

## What is Graphify?

Graphify is a Neo4j unmanaged extension by kbastani for document and text classification using graph-based hierarchical pattern recognition.
- GitHub: https://github.com/kbastani/graphify
- Site: https://graphify.github.io/graphify

## What to do when invoked

Greet the user and ask what they want to do with Graphify. Then help with any of the following:

### 1. Graph Schema Design
Help design Neo4j node and relationship schemas for their data (e.g. COCO annotations, documents, text corpora).

### 2. Cypher Queries
Write Cypher queries for Neo4j to:
- Import/export data to/from graphify
- Query graph patterns
- Run classification or pattern matching

### 3. Graphify API Usage
Help the user call the graphify REST API endpoints:
- `POST /graphify/api/classify` — classify a document
- `POST /graphify/api/training` — submit training data
- `GET /graphify/api/status` — check extension status

### 4. Python Integration
Write Python code to interact with Neo4j + graphify using the `neo4j` driver or `requests` for the REST API.

### 5. COCO + Graphify
Help export COCO dataset annotations into a Neo4j graph so images, categories, and annotations become graph nodes and relationships.

## Activation message

When invoked, respond with:

---

**Graphify is active.** 

I can help you with:
- Designing Neo4j graph schemas
- Writing Cypher queries
- Calling the Graphify REST API
- Python integration with Neo4j
- Exporting COCO data into a graph

What would you like to do?
