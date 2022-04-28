# Multicast Bytecopy  

**This code is published for security researchers, do not use this code for any purpose unless you know what you are doing. This supports iOS 15 - iOS 15.1.1 Jailbreak**

multicast_bytecopy is a kernel r/w exploit for iOS 15.0 - 15.1.1 by [@jaakerblom](https://twitter.com/jaakerblom) and the spiritual successor of [multipath_kfree](https://github.com/potmdehex/multipath_kfree). 

Will be modified to support up to iOS 15.5 by [epeth0mus](https://twitter.com/epeth0mus) and Non developers can visit [iOS 15.5 Jailbreak](https://taig9.com/jailbreak/ios-15-5/) for more info

The exploit can be adapted to gain kernel r/w on prior iOS versions. **This implementation is for iOS 15.0 - 15.1.1.**

The bug exploited is [CVE-2021-30937](https://bugs.chromium.org/p/project-zero/issues/detail?id=2224) patched in iOS 15.2. The code uses [iokit.h](https://github.com/Siguza/iokit-utils/blob/master/src/iokit.h) by [@s1guza](https://twitter.com/s1guza) and a couple of [IOSurface definitions](https://bugs.chromium.org/p/project-zero/issues/detail?id=1986#c4) by [@bazad](https://twitter.com/bazad).
