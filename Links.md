## Good info about designs patterns
https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs

## Good HTTP Client Extensions / Helpers
https://github.com/kim-dam-groenhoej/Polly

## Good Automatic Testing
*It works good with .Net Core and Azure Devops build test*

https://xunit.github.io/

## Good Helpers to ensure quality and avoid mistakes/errors
https://github.com/kim-dam-groenhoej/guard

https://github.com/danielwertheim/ensure.that

## Good logging and notifier about error
https://nlog-project.org/

https://github.com/ElmahCore/ElmahCore

## Force .Net Core version
```
<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    <TargetFramework>netcoreapp2.1</TargetFramework>
    <RuntimeFrameworkVersion>2.1.5</RuntimeFrameworkVersion>
  </PropertyGroup>
  
  <ItemGroup>
    <PackageReference Include="Microsoft.AspNetCore.All" Version="2.1.5" />
  </ItemGroup>
</Project>```

## Force better compiled code for .Net Core 2.1 and .Net standard
*In .NET Core 3 TieredCompilation will be default true*

```<Project Sdk="Microsoft.NET.Sdk">

  <PropertyGroup>
    <TieredCompilation>true</TieredCompilation>
  </PropertyGroup>
</Project>```

## IMPORTANT bug notes
- Dont use System.Net.Http 4.3.3. Bug with disposing Content - Remember look related Links in the bottom for the link - https://github.com/dotnet/corefx/pull/19082
