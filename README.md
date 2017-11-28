# UnityIssueFix
Unity5 - iPhone X Resolution Fix (Letter Box)

These Scripts can be used modifying resolution Unity Game of iPhone X.
To use this function, 
1. Add this script in unity playbackengines (ex) /Applications/Unity/PlaybackEngines/iOSSupport/Trampoline/Classes
2. Modify Trampoline scripts. (UI/UnityViewController+ViewHandling.mm::showGameUI, Unity/DisplayManager.mm::recreateSurface)
3. Open xcode trampoline project(Unity-iPhone.xcodeproj), Add 2 scripts(iPhoneXResolutionMethod.h, iPhoneXResolutionMethod.mm) to Same Group.
