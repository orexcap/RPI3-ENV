# RPI3-ENV
Raspberry PI 3 Environment Setup

## Installing VS Code
Identify ARM 
<pre>
uname -m
armv7l</pre>
Get [Latest Node.js](https://nodejs.org/en/download/) for RPI3 [ARMv7l](https://nodejs.org/dist/v12.16.1/node-v12.16.1-linux-armv7l.tar.xz).

## Installing .NET Core 3.1

[Official Steps](https://dotnet.microsoft.com/download/dotnet-core/thank-you/sdk-3.1.201-linux-arm32-binaries).

Get .NET Core [SDK 3.1.201 for ARM32](https://download.visualstudio.microsoft.com/download/pr/ccbcbf70-9911-40b1-a8cf-e018a13e720e/03c0621c6510f9c6f4cca6951f2cc1a4/dotnet-sdk-3.1.201-linux-arm.tar.gz)

<pre>
mkdir -p $HOME/dotnet && tar zxf dotnet-sdk-3.1.201-linux-arm.tar.gz -C $HOME/dotnet
export DOTNET_ROOT=$HOME/dotnet
export PATH=$PATH:$HOME/dotnet
</pre>
