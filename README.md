1.Login → User logs in to the app.
2.Create tokens → Server gives two tokens:
   Access Token (short time)
   Refresh Token (long time)
3.Use access token → Used to open protected pages or APIs.
4.Access token expires → After some time, it stops working.
5.Send refresh token → App sends the refresh token to the server.
6.Server checks it → Server verifies if the refresh token is valid.
7.Get new access token → Server gives a new access token.
8.Continue using app → User keeps using the app without logging in again.
9.Logout → Refresh token is deleted when the user logs out.
10.Done! → Secure login system with auto token refresh.
