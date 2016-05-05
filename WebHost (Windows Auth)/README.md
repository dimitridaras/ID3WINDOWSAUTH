Identity Server plus Windows Auth
======================================

This project contains three projects:

1. WindowsAuthWebHost - This hosts the IdentityServer.WindowsAuthentication component, which converts windows tokens to identity tokens. 
2. Web Host - An instance of IdentityServer3, which is configured to consume the above component via WS-Federation. 
3. A sample web API, which we want to protect.
