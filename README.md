# mmMacCatalist6_BugReport

```sh

dotnet workload list 

Installed Workload Id      Manifest Version       Installation Source
---------------------------------------------------------------------
macos                      13.3.7067/7.0.100      SDK 7.0.300        
maui-maccatalyst           7.0.86/7.0.100         SDK 7.0.300        
maui-ios                   7.0.86/7.0.100         SDK 7.0.300        
maui-android               7.0.86/7.0.100         SDK 7.0.300        
ios                        16.4.7067/7.0.100      SDK 7.0.300        
maccatalyst                16.4.7067/7.0.100      SDK 7.0.300        

dotnet new maui -n mmMacCatalist6 -f net6.0
cd mmMacCatalist6

dotnet run
The launch profile "(Default)" could not be applied.
A usable launch profile could not be located.
/Users/marti/Code/maui/mmMacCatalist6_BugReport/mmMacCatalist6.csproj : error NU1102: Unable to find package Microsoft.MacCatalyst.Ref with version (= 16.4.60)
/Users/marti/Code/maui/mmMacCatalist6_BugReport/mmMacCatalist6.csproj : error NU1102:   - Found 59 version(s) in nuget.org [ Nearest version: 16.4.7054 ]
/Users/marti/Code/maui/mmMacCatalist6_BugReport/mmMacCatalist6.csproj : error NU1102:   - Found 0 version(s) in /usr/local/share/dotnet/library-packs




```
