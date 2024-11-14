# jdev-test

maven module with several testing dependencies for SDLC.

## How to use it ?

This is not pushed to Maven central... yet. But still you can use it
via [jitpack.io](https://jitpack.io/docs/).

Add the jitpack repository to your maven repositories:

 ```
<repositories>
    ...
    <repository>
        <id>JitPack</id>
        <url>https://jitpack.io</url>
    </repository>
    ...
</repositories>
 ```

Then, add the following to your pom.xml (use any version
from [gitHub releases page](https://github.com/gentjankolicaj/jdev-test/releases)):

 ```
<dependency>
    <groupId>com.github.gentjankolicaj</groupId>
    <artifactId>jdev-test</artifactId>
    <version>main-SNAPSHOT</version>
</dependency>
 ```

