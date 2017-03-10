# How to contribute
One of the easiest ways to contribute is to participate in discussions and discuss issues. You can also contribute by opening an issue and submitting a pull request with code changes.

## General feedback and discussions
For any Service Fabric discussions or feedback not related to a specific repo, please start a discussion in the [service-fabric-issues repo](https://github.com/Azure/service-fabric-issues).

## Bugs and feature requests
For non-security related bugs please log a new issue in the appropriate GitHub repo.

- [Reliable Services, Reliable Actors, and Service Remoting](https://github.com/Azure/service-fabric-services-and-actors-dotnet)
- [ASP.NET Core integration](https://github.com/Azure/service-fabric-aspnetcore)
- [All other bugs or feature requests](http://github.com/Azure/service-fabric-issues)

## Reporting security issues and bugs
Security issues and bugs should be reported privately, via email, to the Microsoft Security Response Center (MSRC)  secure@microsoft.com. You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Further information, including the MSRC PGP key, can be found in the [Security TechCenter](https://technet.microsoft.com/en-us/security/ff852094.aspx).

## Other discussions
For general "how-to" and guidance questions and discussions, please use [Stack Overflow](http://stackoverflow.com/questions/tagged/azure-service-fabric) tagged with `azure-service-fabric`.

## Filing issues 
The best way to get a bug fixed is to be as detailed as you can be about the problem. Providing a minimal project with steps to reproduce the problem is ideal. Here are questions you can answer before you file a bug to make sure you're not missing any important information.

1. Did you read the [documentation](https://docs.microsoft.com/azure/service-fabric)?
2. Did you include the snippet of broken code in the issue?
3. What are the *exact* steps to reproduce this problem?
4. What runtime and SDK versions are you using?
5. What operating system are you using?

GitHub supports [markdown](https://help.github.com/categories/writing-on-github/), so when filing bugs make sure you check the formatting before clicking submit.

## Contributing code and content
### Contributor License Agreement
You will need to sign the [Microsoft Contributor License Agreement](https://cla.microsoft.com/) before submitting your pull request. This needs to be done only once for any Microsoft-sponsored OSS project - if you've signed the Microsoft CLA for any project sponsored by Microsoft, then you are good to go for all the repos sponsored by Microsoft.

 > **Important**: Note that there are **two** different CLAs commonly used by Microsoft projects: [Microsoft CLA](https://cla.microsoft.com/) and [.NET Foundation CLA](https://cla2.dotnetfoundation.org/). Service Fabric OSS projects use the [Microsoft](https://cla.microsoft.com/) CLA. The .NET Foundation is treated as a separate entity, so if you've signed the .NET Foundation CLA in the past, you will still need to sign the Microsoft CLA to contribute to Service Fabric OSS projects.

### Code contribution guidelines
#### Getting started
Make sure you can build the code. Familiarize yourself with the project workflow and our coding conventions. If you don't know what a pull request is, start by reading the [GitHub help on pull requests](https://help.github.com/articles/about-pull-requests/). 
You might also read these two blogs posts on contributing code: [Open Source Contribution Etiquette](http://tirania.org/blog/archive/2010/Dec-31.html) by Miguel de Icaza and [Don't "Push" Your Pull Requests](https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/) by Ilya Grigorik.

#### Submissions
Before submitting a feature or substantial code contribution please discuss it with the team by opening an issue in the repo so that you can get input from the community and the product team, including alignment with the larger product roadmap. 
The Service Fabric team will review and discuss code changes with you in an issue on the repo, so please link your PR to an issue. Once a code change is accepted, we will merge into the *develop* branch on GitHub so others can see it and build on it, and we will also integrate your changes into our internal development branch. 