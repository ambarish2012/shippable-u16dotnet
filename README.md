# seniorquico/u16dotnet

A custom build machine image for Shippable (https://www.shippable.com) based on the [official, base Ubuntu 16.04 build machine image](https://hub.docker.com/r/drydock/u16/). This custom image includes the `mono-devel` package that provides MSBuild and the .NET Compiler Platform ("Roslyn"). This may be used to build .NET Framework projects.

The tags are named according to the template "<Base Image Tag>-<Mono Package Version>".
