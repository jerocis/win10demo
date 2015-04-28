#Windows 10 SDK Demo

##Introduction
I couldn't wait for the release of all the official demos of the Windows 10 SDK. Of course there are some of them already available https://github.com/Microsoft/Windows-universal-samples but some are missing. The purpose of this project is very simple :
- give everyone the opportunity to play with the APIs right now
- share my enthusiasm for the new platform

##What's in ?
100% of the source code is available. It's full C# & XAML.
You will find a Visual Studio solution (Win10Demo.sln) including 3 projects
- The main app (Win10Demo.csproj)
- The secondary app for the app to app communication scenarii (Win10Demo2.csproj)
- The AppService project (Win10DemoService.csproj)
Each feature is illustrated in a single file. Ex : 
There no external dependency or third party library.

##Requirements
A machine with
- Windows 10 Technical Preview Build >=10041
- Visual Studio 2015 CTP 6
- Windows 10 Technical Preview Tools

##What's new?
04/22/2015 Initial release

##Q&A
#### Q: Hum, a sample doesn't work on my machine :S
A: The code was written on Windows 10 build 10061 with Visual Studio 2015 CTP 6. It is still a work in progress project. Your feedback is very welcome. Create an issue or a pull request on Github :)
#### Q: Are those example better that the official samples ?
A: No, they are different. Microsoft is investing a lot of energy to create awesome samples.

If you have any problem with the scripts, use GitHub or contact me on Twitter @danvy

##Special thanks
To Sébastien Pertus @sebastienpertus for his contribution to the SplitView demo
