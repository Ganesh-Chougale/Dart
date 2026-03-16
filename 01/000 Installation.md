#### Terminal:  
`Windows` + `x` + `a`
```Terminal
winget search dart
```  
#### Output:  
```Terminal
PS C:\Users\gchou> winget search dart
Name                      Id                               Version       Match     Source
------------------------------------------------------------------------------------------
DART Sim Pro              9PJNL3KQPGPL                     Unknown                 msstore
Darts Score Tracker       9PPLFTJ03N6F                     Unknown                 msstore
Darts counter             9P9LKWXHKDL7                     Unknown                 msstore
EasyDarts                 9PDKDSVDTLFF                     Unknown                 msstore
Darts Score Master        9NBLGGH6D2JR                     Unknown                 msstore
C# to Dart Transpiler     9P5BNFRSMQ00                     Unknown                 msstore
BlueBubbles               BlueBubbles.BlueBubbles          1.15.0        Tag: dart winget
Nexus Tools               CorbinDavenport.NexusTools       5.8           Tag: dart winget
Dart SDK                  Google.DartSDK                   3.11.2        Tag: dart winget
IIUM Schedule             MuhammadFareezIqmal.IIUMSchedule 1.4.9.0       Tag: dart winget
PingDD                    DarthDemono.PingDD               1.1.2                   winget
Dart SDK - stable channel Gekorm.Dart.stable               1.6.0                   winget
CalendarTask              XiaoweiCloud.CalendarTask        3.26.260.8238           winget
dockerbeam                cryptodarth.dockerbeam           0.1.0.0                 winget
```  
#### Terminal:  
```Terminal
winget install --id Google.DartSDK -e
```  
Explanation:
- `--id Google.DartSDK` → installs the exact package
- `-e` → exact match (avoids installing the wrong thing)  

#### Terminal: verify instalaltion  
```Terminal
dart --version
```  
#### Output:  
```Terminal
Dart SDK version: 3.11.0 (stable) (Mon Feb 9 00:38:07 2026 -0800) on "windows_x64"
```  

for Rapid testing & learning use official web compiler  
`https://dartpad.dev/`  