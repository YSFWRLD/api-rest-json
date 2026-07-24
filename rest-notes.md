# REST Notes

One REST convention is that URL paths should use nouns to describe resources, while the HTTP method expresses the action. For example, `/api/posts` identifies the posts resource, and methods such as GET, POST, PATCH, and DELETE determine what happens to it.

Another convention is that resource identity belongs in the path, while optional controls belong in the query string. For example, `/api/posts/3` identifies post 3, while `/api/posts?page=2&limit=5` controls pagination without identifying a different type of resource.

REST is stateless, which means every request must contain all the information the server needs to understand and process it without relying on a previous request.
