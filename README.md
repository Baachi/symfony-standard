This fork shows the issue with the doctrine profiler.

Just install the components with composer, start the server and visit the default page.
The default page execute a database query through a the doctrine/dbal.

Now look at the profiler and you will see, that the query can't be explained.
