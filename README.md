setup-dotnet
Basic validation e2e tests

This action sets up a .NET CLI environment for use in actions by:

optionally downloading and caching a version(s) of dotnet by SDK version(s) and adding to PATH
registering problem matchers for error output
setting up authentication to private package sources like GitHub Packages
