# Introduction
Multiple PostgreSQL Cluster which supports application smoothly ported from PostgreSQL

# Goals
- Implemented with PostgreSQL extension, which decouple with PostgreSQL, and make it easily for PostgreSQL code upgrade.
- Seperate SQL into 2 parts: PostgreSQL & Distributed SQL, so that application doesn't need to change SQL in code when changing from 1 PostgreSQL to mpg.

