# Add document/template engine

Implement a document/template engine similar to the Cover-Letter-Generator project. This would allow the app to produce formatted Word or PDF documents based on data and templates. The feature would introduce a new subsystem for generating files from structured inputs, which is currently not present in the API.

**Benefits:**
- Ability to produce printable reports or letters
- Reuse templates for different output types

**Tasks:**
1. Investigate python-docx or other libraries
2. Define a template format and placeholder syntax
3. Add API endpoints or CLI commands to generate documents
