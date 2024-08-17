# GraphQL Supabase FastAPI - Serverless

- There is an accompanying NextJS frontend
- This API provides CRUD functionality for the business card DB and generates a png image of a new card using Pillow library when card entries are created in the DB

## GraphQL

- Using [Strawberry](https://github.com/strawberry-graphql/strawberry) library 

## Supabase

- Uses Supabase Auth
- Using [supabase-py](https://github.com/supabase-community/supabase-py)
- This works with RLS which is offered by supabase (optional)
- Uses the Storage buckets and Postgres DB offered by Supabase

## Serverless Function

- This API is deployed as a Serverless Function on Vercel


