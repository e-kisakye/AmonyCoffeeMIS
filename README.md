# Instructions

Languages used: C#

Web framework: .NET 7

To run this project, do the following:

Download .NET 7 SDK here - https://dotnet.microsoft.com/en-us/download/dotnet/7.0

Run the installer and in the terminal run: 

```dotnet --version```

Output should show the dotnet version installed



Within VS code terminal, run the following commands:

Build the app:

```dotnet build```

Install certs required for the app to run:

```dotnet dev-certs https --trust```

NB: After running this command, reopen your browser


Run the app: 

```dotnet run```

Access the application on this URL: https://localhost:7208/



To run this project using docker, do the following:

-Install Docker on your machine.

Once you have Docker installed, you can build the image for the application by running the following command:

```docker build -t amony-coffee-mis .```
To run the application, you can use the following command:

```docker-compose up```
This will start the application and the database container.

You can then access the application at http://localhost:5000

