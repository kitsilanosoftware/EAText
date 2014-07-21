EAText
=============

This is EA's Text rendering library, re-constucted from the partial releases
which EA have made at http://gpl.ea.com.

This repo was put together by Kitsilano Software in the hope that EA will fork it back,
and start maintaining these releases in a form which is actually usable, rather than just
meeting the bare-bones legal and technical requirement to get EAWebKit buildable.

See http://bobsummerwill.wordpress.com/2014/06/25/ea-open-source-software/.

Bob Summerwill, Kitsilano Software, July 2014.

Dependencies
=============
This package depends on the following pacakges:

- [coreallocator](https://github.com/kitsilanosoftware/coreallocator "coreallocator") located at [git@github.com:kitsilanosoftware/coreallocator.git](git@github.com:kitsilanosoftware/coreallocator.git "git@github.com:kitsilanosoftware/EABase.git")
- [EABase](https://github.com/kitsilanosoftware/EABase "EABase") located at [git@github.com:kitsilanosoftware/EABase.git](git@github.com:kitsilanosoftware/EABase.git "git@github.com:kitsilanosoftware/EABase.git")
- [EASTL](https://github.com/kitsilanosoftware/EASTL "EASTL") located at [git@github.com:kitsilanosoftware/EASTL.git](git@github.com:kitsilanosoftware/EASTL.git "git@github.com:kitsilanosoftware/EASTL.git")
- [PPMalloc](https://github.com/kitsilanosoftware/PPMalloc "PPMalloc") located at [git@github.com:kitsilanosoftware/PPMalloc.git](git@github.com:kitsilanosoftware/PPMalloc.git "git@github.com:kitsilanosoftware/PPMalloc.git")
- [FreeType](https://github.com/kitsilanosoftware/FreeType "FreeType") located at [git@github.com:kitsilanosoftware/FreeType.git](git@github.com:kitsilanosoftware/FreeType.git "git@github.com:kitsilanosoftware/PPMalloc.git")
- [EAAssert](https://github.com/kitsilanosoftware/EAAssert "EAAssert") located at [git@github.com:kitsilanosoftware/EAAssert.git](git@github.com:kitsilanosoftware/EAAssert.git "git@github.com:kitsilanosoftware/EAAssert.git")
- [EAIO](https://github.com/kitsilanosoftware/EAIO "EAIO") located at [git@github.com:kitsilanosoftware/EAIO.git](git@github.com:kitsilanosoftware/EAIO.git "git@github.com:kitsilanosoftware/EAIO.git")


Building
=============
Place this package and all its dependencies in the same folder and use MSBuild or Visual Studio to build. 
