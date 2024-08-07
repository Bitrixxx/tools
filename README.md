# tools

This repository contains examples of the default .NET templates provided by Microsoft. These templates include a console application, a web API service, and a web application.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download/dotnet) installed on your machine.
- A command-line interface (CLI) to run the commands.

## Templates Included

1. **Console Application**: A simple console application.
2. **Web API Service**: A basic web API service.
3. **Web Application**: A basic web application.

## Running the Applications

### Console Application

To run the console application, navigate to the `dotnet_service` directory and use the following command:

```bash
sudo dotnet run dotnet_service.dll
```

### Web API Service

To run the web API service, navigate to the `dotnet_web` directory and use the following command:

```bash
sudo dotnet run dotnet_web.dll
```

Once the service is running, you can access it at [http://localhost:5095](http://localhost:5095).

### Web Application

To run the web application, navigate to the `dotnet_webapp` directory and use the following command:

```bash
sudo dotnet run dotnet_webapp.dll
```

Once the application is running, you can access it at [http://localhost:5033](http://localhost:5033).

## Additional Information

For more details on the default .NET templates and how to use them, refer to the [official Microsoft documentation](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new-sdk-templates).

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

node-js-service
PORT=19000 node index.js
http://localhost:19000/api