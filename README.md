# dotnet-tools

A list of tool extensions for .NET Core Command Line (dotnet CLI).

These tools can be installed by executing

    dotnet tool install -g $packageId

After installing, the tool should be available by running

    $commandName

You don't need to run `"dotnet $commandName"`, just `$commandName`

The CLI also supports an older format called "project tools" or `<DotNetCliToolReference>`. A list of project tools is [available here](./project-tools.md).

:bulb: Global tools do not need to be named "dotnet-*". This is only a convention used by some authors as a way to indicate a package is meant to be used as part of the `dotnet` command line tool, and not a standalone tool or library reference.

Command           | Package Id | Author | Description
------------------|------------|--------|--------------
`aistdoc` | [Aistant.DocImport](https://www.nuget.org/packages/Aistant.DocImport/) | [@korzh](https://github.com/korzh) | Generates an API reference docs for .NET code (based on XML Documentation comments) and publishes them on the web
`altcover` | [altcover.global](https://www.nuget.org/packages/altcover.global/) | [@SteveGilham](https://github.com/SteveGilham) | Cross-platform code line and branch coverage tool-set for .net core/.net framework/mono
`altcover.visualizer` | [altcover.visualizer](https://www.nuget.org/packages/altcover.visualizer/) | [@SteveGilham](https://github.com/SteveGilham) | Code coverage display tool to show which parts of your code _aren't_ being covered.  Requires GTK+3 installed separately
`azuresigntool` | [azuresigntool](https://www.nuget.org/packages/AzureSignTool/) | [@vcsjones](https://github.com/vcsjones) | Code sign your files using an Authenticode certificate stored in Azure Key Vault [GitHub](https://github.com/vcsjones/AzureSignTool)
`certes` | [dotnet-certes](https://www.nuget.org/packages/dotnet-certes/) | [@fszlin](https://github.com/fszlin) | CLI tool for acquire certificates via the Automated Certificate Management Environment (ACME) protocol (example: LetsEncrypt.org)  [GitHub](https://github.com/fszlin/certes)
`cleanup` | [dotnet-cleanup](https://www.nuget.org/packages/dotnet-cleanup/) | [@sebnilsson](https://github.com/sebnilsson) | .NET Core Global Tool for cleaning up solution, project or folder. [GitHub](https://github.com/sebnilsson/DotnetCleanup)
`coverlet` | [coverlet.console](https://www.nuget.org/packages/coverlet.console/) | [@tonerdo](https://github.com/tonerdo) | Coverlet is a cross platform code coverage library for .NET Core, with support for line, branch and method coverage. [GitHub](https://github.com/tonerdo/coverlet)
`dmd5` | [dmd5](https://www.nuget.org/packages/dmd5) | [@Rwing](https://github.com/Rwing) | Just generate MD5 hash value in CLI.  [GitHub](https://github.com/Rwing/Dotnet.Tool.MD5)
`docker-watch` | [docker-watch](https://www.nuget.org/packages/docker-watch) | [@nickvdyck](https://github.com/nickvdyck) | A command line utility to notify docker mounted volumes about changes on Windows.  [GitHub](https://github.com/nickvdyck/docker-watch)
`docs` | [dotnet-doc](https://www.nuget.org/packages/dotnet-doc/) | [@spboyer](https://github.com/spboyer) | Search [docs.microsoft.com](https://docs.microsoft.com) using the command line.  [GitHub](https://github.com/spboyer/dotnet-doc)
`dotnet-aop` | [dotnet-aop](https://www.nuget.org/packages/dotnet-aop) | [@ignatandrei](https://github.com/ignatandrei/) | A tool to make AOP for .cs files for your CI pipeline.  [GitHub](https://github.com/ignatandrei/AOP_With_Roslyn)
`dotnet-aspnet-codegenerator` | [dotnet-aspnet-codegenerator](https://www.nuget.org/packages/dotnet-aspnet-codegenerator/) | [@aspnet](https://github.com/aspnet)  | Code generation tool for creating controllers, views, and models in ASP.NET Core projects.   [GitHub](https://github.com/aspnet/Scaffolding)
`dotnet-cake` |  [Cake.Tool](https://www.nuget.org/packages/Cake.Tool/) | [@cake-build](https://github.com/cake-build/) | A tool to run cross platform Cake build scripts. [GitHub](https://github.com/cake-build/cake)
`dotnet-config2json` | [dotnet-config2json](https://www.nuget.org/packages/dotnet-config2json/) | [@andrewlock](https://github.com/andrewlock/) | A simple tool to convert a web.config file to an appsettings.json file.  [GitHub](https://github.com/andrewlock/dotnet-config2json)
`dotnet-cowsay` | [dotnet-cowsay](https://www.nuget.org/packages/dotnet-cowsay/) | [@isaac2004](https://github.com/isaac2004) |CLI Tool that gives a a random blog post from discoverdot.net in cowsay format.  [GitHub](https://github.com/isaac2004/dotnet-cowsay/)
`dotnet-dbinfo` | [dotnet-dbinfo](https://www.nuget.org/packages/dotnet-dbinfo/) | [@berkid89](https://github.com/berkid89) | A simple cross-platform command-line tool for get useful database information (in json format).  [GitHub](https://github.com/berkid89/dotnet-dbinfo)
`dotnet-depends` | [dotnet-depends](https://www.nuget.org/packages/dotnet-depends/) | [@mholo65](https://github.com/mholo65) | Dependency explorer for .NET. [Github](https://github.com/mholo65/depends)
`dotnet-eb` | [Amazon.ElasticBeanstalk.Tools](https://www.nuget.org/packages/Amazon.ElasticBeanstalk.Tools/) | [@aws](https://github.com/aws) | Tools to deploy ASP.NET Core apps to AWS Elastic Beanstalk. Global tool started at version 3.0.0. [Github](https://github.com/aws/aws-extensions-for-dotnet-cli)
`dotnet-ecs` | [Amazon.ECS.Tools](https://www.nuget.org/packages/Amazon.ECS.Tools/) | [@aws](https://github.com/aws) | Tools to deploy containers to Amazon Elastic Container Service functions. Global tool started at version 3.0.0. [Github](https://github.com/aws/aws-extensions-for-dotnet-cli)
`dotnet-encrypto` | [dotnet-encrypto](https://www.nuget.org/packages/dotnet-encrypto) | [@tomchavakis](https://github.com/tomchavakis) | A tool to encrypt/decrypt folder or files using AES 256 Encryption Algorithm [Github](https://github.com/tomchavakis/encrypto)
`dotnet-fm` | [FluentMigrator.DotNet.Cli](https://www.nuget.org/packages/FluentMigrator.DotNet.Cli/) | [@FluentMigrator](https://github.com/fluentmigrator) | FluentMigrator: Is a database migration framework for .NET much like Ruby on Rails Migrations.  [GitHub](https://fluentmigrator.github.io/articles/runners/dotnet-fm.html)
`dotnet-fsharplint` | [FSharpLint](https://www.nuget.org/packages/dotnet-fsharplint/) | [@fsprojects](https://github.com/fsprojects) | Lint tool for F#. [GitHub](https://github.com/fsprojects/FSharpLint) |
`dotnet-gitversion` | [GitVersion.Tool](https://www.nuget.org/packages/GitVersion.Tool) | [@GitTools](https://github.com/GitTools) | Easy Semantic Versioning (http://semver.org) for projects using Git. [GitHub](https://github.com/GitTools/GitVersion)
`dotnet-gitreleasemanager` | [GitReleaseManager.Tool](https://www.nuget.org/packages/GitReleaseManager.Tool) | [@GitTools](https://github.com/GitTools) | Tool for creating and exporting releases for software applications hosted on Github
`dotnet-hash` | [TheBlueSky.DotNet.Tools.SwiftHash](https://www.nuget.org/packages/TheBlueSky.DotNet.Tools.SwiftHash/) | [@TheBlueSky](https://github.com/TheBlueSky) | A simple dotnet tool to calculate hashes for the given file. [GitHub](https://github.com/TheBlueSky/dotnet-hash)
`dotnet-ignore` | [dotnet-ignore](https://www.nuget.org/packages/dotnet-ignore/) | [@Arasz](https://github.com/Arasz) | Global .NET Core tool that can download .gitignore file from github gitignore repository.  [GitHub](https://github.com/Arasz/dotnet-ignore)
`dotnet-install` | [QB.DotNetCoreInstaller](https://www.nuget.org/packages/QB.DotNetCoreInstaller/) | [@jaurenq](https://github.com/jaurenq) | Provides capabilities for installing a .NET Core shared runtime. [Github](https://github.com/jaurenq/QB.DotNetCoreInstaller)
`dotnet-lambda` | [Amazon.Lambda.Tools](https://www.nuget.org/packages/Amazon.Lambda.Tools/) | [@aws](https://github.com/aws) | Tools to deploy AWS Lambda functions. Global tool started at version 3.0.0. [Github](https://github.com/aws/aws-extensions-for-dotnet-cli)
`dotnet-migrate-2017` | [Project2015To2017.Migrate2017.Tool](https://www.nuget.org/packages/Project2015To2017.Migrate2017.Tool) | [@hvanbakel](https://github.com/hvanbakel) | Tool for converting a MSBuild project file (`csproj`) to VS2017 format and beyond. [GitHub](https://github.com/hvanbakel/CsprojToVs2017)
`dotnet-nuget-gc` | [dotnet-nuget-gc](https://nuget.org/packages/dotnet-nuget-gc) | [@terrajobst](https://github.com/terrajobst) | A tool for cleaning the NuGet cache. [GitHub](https://github.com/terrajobst/dotnet-nuget-gc)
`dotnet-obfuscar` | [Obfuscar.GlobalTool](https://www.nuget.org/packages/Obfuscar.GlobalTool/) | [@lextm](https://github.com/lextm) | A .NET Core global tool to obfuscate assemblies.  [GitHub](https://github.com/obfuscar/obfuscar)
`dotnet-outdated` | [dotnet-outdated](https://www.nuget.org/packages/dotnet-outdated/) | [@jerriep](https://github.com/jerriep) | A .NET Core global tool to display outdated NuGet packages in a project.  [GitHub](https://github.com/jerriep/dotnet-outdated)
`dotnet-property`| [dotnet-property](https://www.nuget.org/packages/dotnet-property) | [@pwelter34](https://github.com/loresoft) | .NET Core command-line (CLI) tool to update project properties and version numbers on build. [GitHub](https://github.com/loresoft/DotNet.Property)
`dotnet-retire`| [dotnet-retire](https://www.nuget.org/packages/dotnet-retire) | [@johnkors](https://github.com/johnkors) |  A dotnet CLI extension to check your project for known vulnerabilities. [GitHub](https://github.com/retirenet/dotnet-retire)
`dotnet-runas`| [dotnet-runas](https://www.nuget.org/packages/dotnet-runas) | [@NikolayPianikov](https://github.com/NikolayPianikov) |  Allows to run a dotnet process under a specified user account. [GitHub](https://github.com/JetBrains/runAs)
`dotnet-script` | [dotnet-script](https://www.nuget.org/packages/dotnet-script/) | [@filipw](https://github.com/filipw) [@seesharper](https://github.com/seesharper) | Run C# scripts from the .NET CLI.  [GitHub](https://github.com/filipw/dotnet-script)
`dotnet-search` | [dotnet-search](https://www.nuget.org/packages/dotnet-search/) | [@billpratt](https://github.com/billpratt) | Search for Nuget packages using the .NET Core CLI.  [GitHub](https://github.com/billpratt/dotnet-search)
`dotnet-serve` | [dotnet-serve](https://www.nuget.org/packages/dotnet-serve/) | [@natemcmaster](https://github.com/natemcmaster) | A simple command line HTTP server, no code required.  [GitHub](https://github.com/natemcmaster/dotnet-serve)
`dotnet-snow` | [dotnet-snow](https://www.nuget.org/packages/dotnet-snow/) | [@ptupitsyn](https://github.com/ptupitsyn) | Avalonia-based cross-platform graphical snow demo.  [GitHub](https://github.com/ptupitsyn/let-it-snow)
`dotnet-sonarscanner` | [dotnet-sonarscanner](https://www.nuget.org/packages/dotnet-sonarscanner) | [@SonarSource](https://github.com/SonarSource) | The SonarScanner for MSBuild is the recommended way to launch a SonarQube or SonarCloud analysis for projects/solutions using dotnet command as build tool.  [GitHub](https://github.com/SonarSource/sonar-scanner-msbuild)
`dotnet-sshdeploy` | [dotnet-sshdeploy](https://www.nuget.org/packages/dotnet-sshdeploy) | [@Unosquare](https://github.com/unosquare) | A dotnet CLI command that enables quick deployments over SSH.  [GitHub](https://github.com/unosquare/sshdeploy)
`dotnet-symbol` | [dotnet-symbol](https://www.nuget.org/packages/dotnet-symbol/) | [@microsoft](https://github.com/microsoft) | Symbols download utility.
`dotnet-t4` | [dotnet-t4](https://www.nuget.org/packages/dotnet-t4/) | [@mhutch](https://github.com/mhutch) | T4 text template processor. [GitHub](https://github.com/mono/t4)
`dotnet-thx` | [DotnetThx](https://www.nuget.org/packages/DotnetThx) | [@krystiankolad](https://github.com/KrystianKolad) | Find authors of packages you are using in you project and visit their GitHub. [Github](https://github.com/KrystianKolad/DotnetThx)
`dotnet-xdt` | [dotnet-xdt](https://www.nuget.org/packages/dotnet-xdt/) | [@nil4](https://github.com/nil4) | Global tool for applying XML Document Transformations to .NET configuration files, or any other XML-structured content.  [GitHub](https://github.com/nil4/dotnet-transform-xdt)
`dotnetrsa` | [dotnetrsa](https://www.nuget.org/packages/dotnetrsa) | [@stulzq](https://github.com/stulzq) | Generate rsa pkcs1, pkcs8, xml format key. Conversion between the three formats.  [GitHub](https://github.com/stulzq/DotnetRSA)
`efg` | [EntityFrameworkCore.Generator](https://www.nuget.org/packages/EntityFrameworkCore.Generator) | [@pwelter34](https://github.com/loresoft) | .NET Core command-line (CLI) tool to generate Entity Framework Core model from an existing database. [GitHub](https://github.com/loresoft/EntityFrameworkCore.Generator)
`fake` | [fake-cli](https://www.nuget.org/packages/fake-cli/) | [@fsharp](https://github.com/fsharp) | F# MAKE 5 - A DSL FOR BUILD TASKS AND MORE. [GitHub](https://github.com/fsharp/Fake)
`flubu` | [FlubuCore.GlobalTool](https://www.nuget.org/packages/FlubuCore.GlobalTool) | [@FlubuCore](https://github.com/flubu-core) | Fluent Builder. A cross platform build automation tool for building projects and executing deployment scripts using C# code.  [GitHub](https://github.com/flubu-core/flubu.core)
`ghi` | [github-issues-cli](https://www.nuget.org/packages/github-issues-cli/) | [@jerriep](https://github.com/jerriep) | A simple command-line client for managing GitHub Issues.  [GitHub](https://github.com/jerriep/github-issues-cli)
`giphy` | [GiphyCli](https://www.nuget.org/packages/GiphyCli/) | [@DavidDeSloovere](https://github.com/DavidDeSloovere) | Find that giphy fast and just copy the url or markdown.  [GitHub](https://github.com/DavidDeSloovere/giphy-cli)
`git-browse` | [git-browse](https://www.nuget.org/packages/git-browse) | [@nickvdyck](https://github.com/nickvdyck) | Open the GitHub page or website for a repository in your browser. [GitHub](https://github.com/nickvdyck/git-browse)
`git-istage` | [git-istage](https://nuget.org/packages/git-istage) | [@terrajobst](https://github.com/terrajobst) | A better git add -p. [GitHub](https://github.com/terrajobst/git-istage)
`git-status` | [git-status-cli](https://www.nuget.org/packages/git-status-cli/) | [@jerriep](https://github.com/jerriep) | A simple command-line utility to determine status of all Git repositories in a directory structure.  [GitHub](https://github.com/jerriep/git-status-cli)
`gti` | [gti](https://www.nuget.org/packages/gti/) | [@shaun-h](https://github.com/shaun-h) | Global tool for installing .Net Global tools from a tools.gti file. [GitHub](https://github.com/shaun-h/gti)
`guid` | [dotnet-guid](https://www.nuget.org/packages/dotnet-guid/) | [@sebnilsson](https://github.com/sebnilsson) | .NET Core Global Tool for creating GUIDs/UUIDs. [GitHub](https://github.com/sebnilsson/DotnetGuid)
`html-copy-vscode` | [HtmlCopyVSCode](https://www.nuget.org/packages/HtmlCopyVSCode/) | [@slang25](https://github.com/slang25/) | A global tool to convert snippets copied from VS Code into plain html to paste into your blog.  [GitHub](https://github.com/slang25/html-copy-vscode)
`idgen` | [IdentifierGenerator](https://www.nuget.org/packages/IdentifierGenerator/) | [@abock](https://github.com/abock) | idgen  supports the bulk generation of various types of unique identifiers. [GitHub](https://github.com/abock/idgen)
`kubedmc` | [kubedmc](https://www.nuget.org/packages/KubeDmc/) | [@mimetis](https://github.com/Mimetis) | Navigate into your favorite Kubernetes cluster with one finger ! [GitHub](https://github.com/Mimetis/Kubedmc)
`libman` | [Microsoft.Web.LibraryManager.CLI](https://www.nuget.org/packages/Microsoft.Web.LibraryManager.CLI) | [@aspnet](https://github.com/aspnet) | LibMan is a tool that helps you download common libraries from the Internet to use in your web project. [GitHub](https://github.com/aspnet/LibraryManager/wiki/Using-LibMan-CLI)
`LocalAppVeyor` | [localappveyor](https://www.nuget.org/packages/localappveyor) | [@joaope](https://github.com/joaope) | .NET Core global tool which brings appveyor.yml to the center of your build process by making possible to execute its build jobs, locally.  [GitHub](https://github.com/joaope/localappveyor)
`minver-cli` | [minver-cli](https://www.nuget.org/packages/minver-cli) | [@adamralph](https://github.com/adamralph) | A minimalistic .NET package for versioning .NET SDK-style projects using Git tags. [GitHub](https://github.com/adamralph/minver)
`nbgv` | [nbgv](https://www.nuget.org/packages/nbgv/) | [@AArnott](https://github.com/AArnott) | A .NET Core Tool that can install, read and set version information based on git history, using Nerdbank.GitVersioning. [GitHub](https://github.com/aarnott/Nerdbank.GitVersioning)
`ndjson` | [ndjson](https://www.nuget.org/packages/ndjson/) | [@fredeil](https://github.com/fredeil) | A dotnet cli tool for printing newline delimited json to console. [GitHub](https://github.com/fredeil/dotnet-ndjson)
`NuGetKeyVaultSignTool` | [NuGetKeyVaultSignTool](https://www.nuget.org/packages/NuGetKeyVaultSignTool/) | [@onovotny](https://github.com/onovotny) | Code sign your .nupkg files using an Authenticode certificate stored in Azure Key Vault [GitHub](https://github.com/onovotny/NuGetKeyVaultSignTool)
`nuget-deploy` | [NuGetUtils.Tool.Deploy](https://www.nuget.org/packages/NuGetUtils.Tool.Deploy/) | [@stazz](https://github.com/stazz) | Restore NuGet package if needed, and deploy it in a specified folder, by copying assemblies of the NuGet dependencies, or by generating appropriate `.deps.json` and `.runtimeconfig.json` files [GitHub](https://github.com/stazz/NuGetUtils/tree/develop/Source/NuGetUtils.Tool.Deploy)
`nuget-exec` | [NuGetUtils.Tool.Exec](https://www.nuget.org/packages/NuGetUtils.Tool.Exec/) | [@stazz](https://github.com/stazz) | Restore NuGet package if needed, and execute a method within its assembly, loading dependencies as needed on-the-fly. Custom method parameter types are also supported. [GitHub](https://github.com/stazz/NuGetUtils/tree/develop/Source/NuGetUtils.Tool.Exec)
`nuget-restore` | [NuGetUtils.Tool.Restore](https://www.nuget.org/packages/NuGetUtils.Tool.Restore/) | [@stazz](https://github.com/stazz) | Restore one or more NuGet package, if needed. [GitHub](https://github.com/stazz/NuGetUtils/tree/develop/Source/NuGetUtils.Tool.Restore)
`nuke` | [Nuke.GlobalTool](https://www.nuget.org/packages/Nuke.GlobalTool) | [@nuke-build](https://github.com/nuke-build) | Run and setup NUKE builds with a single command on any platform :rocket:  [GitHub](https://github.com/nuke-build/nuke)
`NuKeeper` | [NuKeeper](https://www.nuget.org/packages/NuKeeper) | [@AnthonySteele](https://github.com/anthonysteele) | Find outdated NuGet packages and apply updates to them.  [GitHub](https://github.com/NuKeeperDotNet/NuKeeper)
`nyancat` | [nyancat](https://www.nuget.org/packages/nyancat/) | [@nickvdyck](https://github.com/nickvdyck) | Nyancat 😻 in your terminal, rendered through ANSI escape sequences. A port of the original terminal application to make this cat run on dotnet core. 🐱‍🏍  [GitHub](https://github.com/nickvdyck/nyancat.cs)
`otterkeys` | [OtterKeys](https://www.nuget.org/packages/OtterKeys) | [@natsuo](https://github.com/natsuo) | Quickly create Ed25519 key pairs for signing and verifying messages or other data. [GitHub](https://github.com/miqo-no/OtterKeys)
`pbm` | [pbm](https://www.nuget.org/packages/pbm/) | [@petabridge](https://cmd.petabridge.com/) | [Petabridge.Cmd CLI](https://cmd.petabridge.com/) for managing [Akka.NET](http://getakka.net/) applications and clusters   [GitHub](https://github.com/petabridge/petabridge.cmd-issues)
`protogen` | [protobuf-net.Protogen](https://www.nuget.org/packages/protobuf-net.Protogen/) | [@mgravell](https://github.com/mgravell) | protobuf-net code-generation from .proto schema files.   [GitHub](https://github.com/mgravell/protobuf-net)
`reportgenerator` | [dotnet-reportgenerator-globaltool](https://www.nuget.org/packages/dotnet-reportgenerator-globaltool) | [@danielpalme](https://github.com/danielpalme) | ReportGenerator converts XML reports generated by OpenCover, PartCover, dotCover, Visual Studio, NCover or Cobertura into human readable reports in various formats.  [GitHub](https://github.com/danielpalme/ReportGenerator/)
`rider` | [dotnet-rider-cli](https://www.nuget.org/packages/dotnet-rider-cli) | [@markrendle](https://github.com/markrendle) | **Windows only** Adds a `rider` command to launch JetBrains Rider when it's installed via [Toolbox](https://jetbrains.com/toolbox/).  [GitHub](https://github.com/RendleLabs/dotnet-rider-cli/)
`sleet` | [Sleet](https://www.nuget.org/packages/Sleet/) | [@emgarten](https://github.com/emgarten) | A static NuGet feed generator.   [GitHub](https://github.com/emgarten/Sleet)
`srihash` | [srihash-cli](https://www.nuget.org/packages/srihash-cli) | [@natemcmaster](https://github.com/natemcmaster) | Generates the SRI hash for `<script>` tags in browsers  [GitHub](https://github.com/natemcmaster/srihash-cli)
`sysinfo` | [Elemental.SysInfoTool](https://www.nuget.org/packages/Elemental.SysInfoTool/) | [@markpflug](https://github.com/markpflug) | Outputs system information.  [GitHub](https://github.com/markpflug/Elemental.SysInfoTool)
`tcpmux` | [TcpMux](https://www.nuget.org/packages/TcpMux/) | [@nicodeslandes](https://github.com/nicodeslandes) | TCP Multiplexer; provide simple routing of TCP traffic as well as SSL re-encryption and off-loading.  [GitHub](https://github.com/nicodeslandes/TcpMux)
`trx2junit` | [trx2junit](https://www.nuget.org/packages/trx2junit/) | [@gfoidl](https://github.com/gfoidl) | Transforms XML from trx-Testresults to JUnit-Testresults / trx to JUnit XML. [GitHub](https://github.com/gfoidl/trx2junit)
`unpkg` | [RendleLabs.UnpkgCli](https://www.nuget.org/packages/RendleLabs.UnpkgCli) | [@markrendle](https://github.com/markrendle) | Front-end package manager that uses the [unpkg.com](https://unpkg.com) CDN as a source. No Node.js, NPM or Bower required.  [GitHub](https://github.com/RendleLabs/dotnet-unpkg)
`upforgrabs` | [upforgrabs](https://www.nuget.org/packages/upforgrabs) | [@spboyer](https://github.com/spboyer) | A tool to select a random .NET Open Source project/issue tagged with "up-for-grabs","firsttimer", etc. to work on.  [GitHub](https://github.com/spboyer/dotnet-upforgrabs)
`versioninfo` | [dotnet-versioninfo](https://www.nuget.org/packages/dotnet-versioninfo/) | [@taylorjg](https://github.com/taylorjg) | Display version information of .NET Core assemblies. [GitHub](https://github.com/taylorjg/dotnet-versioninfo)
`weeknumber` | [weeknumber](https://www.nuget.org/packages/weeknumber/) | [@MarkusLund](https://github.com/MarkusLund) | Prints the current weeknumber to the command line.  [GitHub](https://github.com/MarkusLund/weeknumber)
`xscgen` | [dotnet-xscgen](https://www.nuget.org/packages/dotnet-xscgen/) | [@mganss](https://github.com/mganss) | Generate XmlSerializer compatible C# classes from XML Schema files.  [GitHub](https://github.com/mganss/XmlSchemaClassGenerator)

<!-- Contributors: when adding a new item to the list, please help me keep this list sorted by command name in alphabetical order. Thanks! -->
