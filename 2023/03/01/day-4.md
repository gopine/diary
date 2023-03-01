Thinking about using Tanstack Query to handle the client state, since it has a great caching and invalidation strategy.

Imported tRPC client to project.

Wrote custom hooks to fetch data.

Implemented Tanstack Query and now the page loads really fast because of the query caching.

But now I have to think about how to invalidate cache properly whenever the data changes.

Will look into `useMutation` hook from Tanstack.

Added more documentation to the project.