# Cinegy MXFstream Analyser Tool

Use this tool to view inbound metadata, network, RTP and TS packet details on Windows, Mac and Linux. 

## How easy is it?

Just run MXFstreamAnalyzer from inside a command-prompt, and you will be offered a basic interactive mode to get cracking checking out your stream.

You can print live Teletext decoding, and you can use the tool to generate input logs for 'big data' analysis (which is very cool).

## Hold on, what makes this special?

At the moment, this tool will accept any valid MXFstream - but it does not yet decode and display any of the MXFstream metadata elements. That functionality will be added shortly!

## Command line arguments:

Double click, or just run without (or with incorrect) arguments, and you'll see this:

```
TODO
```

The help details for the 'stream' verb look like this:

```
TODO
```

We will be adding MSIs for Windows and Debian / Ubuntu packages soon - but currently if you want to run on Linux you need to clone the repository and run 'dotnet build' or 'dotnet publish -r release -c linux-x64' to general binaries.

Mac support is still a work in progress, but once we get multicast working nicely we will create a DMG and add a brew package.

Just to make your life easier, we auto-build this using AppVeyor - here is how we are doing right now for master: 

[![Build status](https://ci.appveyor.com/api/projects/status/cn9vy12bi3a617cx/branch/master?svg=true)](https://ci.appveyor.com/project/cinegy/mxfstreamanalyzer/branch/master)

You can check out the latest compiled binary from the master or pre-master code here:

[AppVeyor MXFstreamAnalyser Project Builder](https://ci.appveyor.com/project/cinegy/mxfstreamanalyzer/build/artifacts)

