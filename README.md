user logs in → Server gives Access Token and Refresh Token.
Access Token is used for all API requests.
Access Token expires after a short time (e.g., 15 mins).
When it expires, the client sends the Refresh Token to the server.
Server checks the Refresh Token → if valid, gives a new Access Token.
Client uses the new Access Token to continue working.
When the Refresh Token also expires, the user must log in again.
On logout, both tokens are deleted.
