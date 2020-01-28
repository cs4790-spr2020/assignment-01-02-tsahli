# BlabberApp

BlabberApp a Twitter-like .NETcore class project

## SSH Tunneling

SSH tunneling or port forwarding is a technique for viewing a remote web server on your local machine.  It makes it look like the web server is running locally when actually it is running in your account on the class server.  Here is detailed information: [SSH Port Forwarding](https://www.ssh.com/ssh/tunneling/example).  Here is an example of my personal port fowarding command:

`ssh 64.225.37.60 -L 5041:localhost:5041 -N`

## Assignment 01 (65 points)

Execute the commands below to setup your BlabberApp solution.

- `mkdir -p BlabberApp`
- `cd BlabberApp`
- `dotnet new sln BlabberApp`
- `dotnet new webapp -o BlabberApp.Client`
- `dotnet new mstest -o BlabberApp.ClientTest`
- `dotnet new console -o BlabberApp.Console`
- `dotnet new webapi -o BlabberApp.WebApi`
- `dotnet new mstest -o BlabberApp.WebApiTest`
- `dotnet new classlib -o BlabberApp.DataStore`
- `dotnet new mstest -o BlabberApp.DataStoreTest`
- `dotnet new classlib -o BlabberApp.Domain`
- `dotnet new mstest -o BlabberApp.DomainTest`

Execute the command below to build your BlabberApp solution: `dotnet build BlabberApp.sln`

If no errors are reported by the commands you have successfully completed the assignment.

## Assignment 02 (20 points)

Execute the following commands to run your BlabberApp.Client.

- `cd BlabberApp/BlabberApp.Client`
- `dotnet run`
- Open your browser
- In the address bar enter `https:\\localhost:5001`.  **NOTE**: If you have changed the port in your `Properties/launchSettings.json` file use that port number instead.
