# Azure Service Fabric 
This repository is the starting point to engage in and learn about Service Fabric open source projects from Microsoft. For more information on Service Fabric, see our [documentation](https://docs.microsoft.com/azure/service-fabric/).

Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable distributed applications. Service Fabric also addresses the significant challenges in developing and managing cloud applications. Developers and administrators can avoid complex infrastructure problems and focus on implementing mission-critical, demanding workloads that are scalable, reliable, and manageable. Service Fabric represents the next-generation middleware platform for building and managing these enterprise-class, tier-1, cloud-scale applications.

## Issues and feature discussion
For issue reporting and feature discussion please use one of the open source project repos listed below where it makes sense. For general Service Fabric issues and discussion that doesn't fall into one of the open source repos, please use the [Azure/service-fabric-issues](https://github.com/azure/service-fabric-issues) repo.

## Service Fabric open source projects 
We are making parts of the SDK source publicly available and open to contributions. This includes the SDK packages found on NuGet, such as Reliable Services, Reliable Actors, Service Remoting, and ASP.NET Core integration. The Service Fabric runtime is not available today as an open source project. As we collect feedback and run tests on contributions, we will determine the best time to open source the runtime, which includes the clustering layers and the Reliable Collections replicated persisted store.

You can find our open source components in the following repos:

**Reliable Services and Reliable Actors**
 - [Azure/service-fabric-services-and-actors-dotnet](https://github.com/Azure/service-fabric-services-and-actors-dotnet)

**ASP.NET Core Service Fabric integration**
 - [Azure/service-fabric-aspnetcore](https://github.com/Azure/service-fabric-aspnetcore)

**Service Fabric CLI (sfctl)**
 - [Azure/service-fabric-cli](https://github.com/Azure/service-fabric-cli)

**Service Fabric Yeoman generators**
 - C#: [Azure/generator-azuresfcsharp](https://github.com/Azure/generator-azuresfcsharp)
 - Java: [Azure/generator-azuresfjava](https://github.com/Azure/generator-azuresfjava)
 - Guest EXEs: [Azure/generator-azuresfguest](https://github.com/Azure/generator-azuresfguest)
 - Containers: [Azure/generator-azuresfcontainer](https://github.com/Azure/generator-azuresfcontainer)


## How we do development 
Before Service Fabric shipped publicly as a product in 2015, it was developed as a Microsoft-internal-only platform for over five years. As a result, much of our development process is still deeply rooted in internal build processes, tools, and test suites. So for the time being we are continuing to do our own development internally. Upon each release of the SDK, we will push our latest changes to GitHub. We intend to bring more of our development process and tools into the open over time.

## How to engage, contribute and provide feedback 
The Service Fabric team accepts pull requests and other contributions on a best-effort basis. If we accept a PR, we will integrate the changes into our internal development repo for testing and verification, and then push the merged changes back to GitHub when the change is released in a new SDK release. The smaller and more targeted your PRs, the easier it will be for us to review and integrate them. 
For more information on how this process works and how to contribute, provide feedback, and log bugs, please see [Contributing.md](CONTRIBUTING.md).

## Documentation 
Service Fabric has a rich set of conceptual and reference documentation available at [docs.microsoft.com/azure/service-fabric](https://docs.microsoft.com/azure/service-fabric/). Documentation is also open to your contribution on GitHub at [github.com/Microsoft/azure-docs](https://github.com/Microsoft/azure-docs).

## Samples 
For Service Fabric sample code, check out the [Azure Code Sample gallery](https://azure.microsoft.com/resources/samples/?service=service-fabric) or go straight to [Azure-Samples on GitHub](https://github.com/Azure-Samples?q=service-fabric).

## License 
All Service Fabric OSS projects are licensed under the [MIT License](LICENSE.txt).

## Code of Conduct 
All Service Fabric OSS projects adopt the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.