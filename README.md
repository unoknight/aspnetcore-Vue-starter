# ASP.NET Core & Vue.js Starter

<a href="https://www.nuget.org/packages/aspnetcore-vuejs/" target="_blank"><img alt="Nuget" src="https://img.shields.io/nuget/v/aspnetcore-vuejs.svg?style=for-the-badge"></a>
<a href="https://www.nuget.org/packages/aspnetcore-vuejs/" target="_blank"><img alt="Nuget" src="https://img.shields.io/nuget/dt/aspnetcore-vuejs.svg?label=Nuget%20Downloads&style=for-the-badge"></a>

---

<br>
<p align="center">
  <a href="https://trilon.io" target="_blank">
        <img width="500" height="auto" src="https://trilon.io/trilon-logo-clear.png" alt="Trilon.io - Angular Universal, NestJS, JavaScript Application Consulting Development and Training">
  </a>
</p>


<h3 align="center"> Made with :heart: by <a href="https://trilon.io">Trilon.io</a></h3>

---


# Table of Contents

* [Features](#features)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Getting Started](#getting-started)
* [Extras](#extras)
* [Special Thanks](#special-thanks)
* [License](#license)
* [Trilon - VueJS & Asp.NET Consulting & Training](#trilon---vue-aspnet-nodejs---consulting--training--development)

# Features

- **ASP.NET Core 2.1**
  - Web API
- **VueJS 2**
  - Vuex (State Store)
- **Webpack**
  - HMR (Hot Module Replacement/Reloading)
- **Bootstrap 4**

# Prerequisites:
 * [.Net Core 2.1](https://www.microsoft.com/net/download/windows)
 * [NodeJS](https://nodejs.org/) >= 8.9.4
 * [VSCode](https://code.visualstudio.com/) (ideally), or VS2017

# Installation:

### Nuget | Dotnet Templates

Find the template through NuGet package manager inside Visual Studio or [here](https://www.nuget.org/packages/aspnetcore-vuejs)

> Or download it via dotnet templates

```ts
// Make a directory where you want the project
mkdir my-vue-starter && cd my-vue-starter

// Download the dotnet template
dotnet new -i aspnetcore-vuejs

// Run and install the template
dotnet new vuejs

// Make sure you install the dependencies
npm install
```

Now you can open the project via Visual Studio or VSCode, press F5 to run the application!

Note: 

* This will automatically run `dotnet restore` unless you install with `dotnet new vuejs --skipRestore`
* ([Official documentation](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new?tabs=netcore2x))
   * This will automatically run `dotnet restore` unless you install with `dotnet new vuejs --skipRestore`

### -OR- Clone this Repo itself

 * Clone this repository : `$ git clone https://github.com/MarkPieszak/aspnetcore-Vue-starter.git VueWeb`
 * `$ cd VueWeb/content`
 * `$ dotnet restore && npm install`
 * (If using VSCode) `$ code .` 
 * (If using Visual Studio) Open the `*.sln` file with "Open project" from Visual Studio IDE


## Start the application:
You have two choices when it come at how your preffer to run it. You can either use the command line or the build-in run command.

### 1. Using the command line
Run the application using `dotnet run` or `npm run dev`
- note `dotnet run` should be run in `Development` environment for hot reloading. This setting can be set either within the command line or via the `launchSettings.json` available in the `Properties` folder.
 
### 2. Using the built-in run command
Run the application in VSCode or Visual Studio 2017 by hitting `F5`.

## View your application running
When running the app using debug menu or `F5` VS open auto the app in the browser;

# Recommended plugin for debugging VueJS

- Get Chrome DevTools for VueJS [here](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)

----

# Found a Bug? Want to Contribute?

Nothing's ever perfect, but please let me know by creating an issue (make sure there isn't an existing one about it already), and we'll try and work out a fix for it! If you have any good ideas, or want to contribute, feel free to either make an Issue with the Proposal, or just make a PR from your Fork.
Please note that this project is released with a [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

----

### Special Thanks

Many thanks go out to Steve Sanderson (@SteveSandersonMS) from Microsoft and his amazing work on [JavaScriptServices](https://blogs.msdn.microsoft.com/webdev/2017/02/14/building-single-page-applications-on-asp-net-core-with-javascriptservices/) and integrating the world of Node with ASP.NET Core.

### Also, a million thanks to key Contributors ! 

- [@Nordes](https://github.com/Nordes) :sparkles:
- [@mika76](https://github.com/mika76) :sparkles:
- [@vip32](https://github.com/vip32) :sparkles:
- [@anderly](https://github.com/anderly) :sparkles:

---

_Looking for ASP.NET Core & Angular 7.x+ Universal starter? [click here](https://github.com/TrilonIO/aspnetcore-angular-universal)_

----

# License

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](/LICENSE) 

Copyright (c) 2016-2019 [Mark Pieszak](https://github.com/MarkPieszak)

[![Twitter Follow](https://img.shields.io/twitter/follow/MarkPieszak.svg?style=social)](https://twitter.com/MarkPieszak)

----

# Trilon - Vue, Asp.NET, NodeJS - Consulting | Training | Development

Check out **[Trilon.io](https://Trilon.io)** for more info! Twitter [@Trilon_io](http://www.twitter.com/Trilon_io)

Contact us at <hello@trilon.io>, and let's talk about your projects needs.

<p align="center">
  <a href="https://trilon.io" target="_blank">
    <img src="https://trilon.io/trilon-logo-clear.png" alt="Trilon.io - Angular Universal, NestJS, JavaScript Application Consulting Development and Training">
  </a>
</p>

## Follow Trilon online:

Twitter: [@Trilon_io](http://twitter.com/Trilon_io)
