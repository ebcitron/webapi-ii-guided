## REFACTORING TO USE ROUTERS

-We created a server.js file and extracted express server code from index, leaving index to only be concerned with listening on the port

-extract all the /api/hubs endpoints into its own hubs-router file

- we instantiate a router via express.Router()
and export that, importing it into the server.js file

-we append the url address we want to use for those endpoints into the server.use method and extract those through hubsRouter from the router file


