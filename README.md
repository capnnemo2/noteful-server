# Noteful API

Once started, this will run a local API server on `http://localhost:8000` by default.

## Endpoints

- /folders
- /notes

Both support GET, POST, PATCH, and DELETE. For PATCH and DELETE requests you must supply the respective id in the endpoint's path.

For example:

- GET /folders
- GET /notes
- POST /folders
- POST /notes
- PATCH /folders/{folder-id}
- PATCH /notes/{note-id}
- DELETE /folders/{folder-id}
- DELETE /notes/{note-id}

## Start server

To start the server, run `npm start`
