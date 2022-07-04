# release-invesdwin-instrument
from https://github.com/invesdwin/invesdwin-instrument

# What is it?
invesdwin-instrument 의 repository 가 불안정해 이 라이브러리를 참조하는 프로젝트를 정상적으로 빌드할 수 없는 문제가 종종 발생한다.
이를 해결하기 위해 invesdwin-instrument v1.0.14 를 fork 해, invesdwin-instrument 의 maven repository 를 대체하고자 한다.

Because the repository of the invesdwin-instrument is unstable, a problem that a project referencing this library cannot be built normally occurs. 
To solve this problem, we fork invesdwin-instrument v1.0.14 and replace the origin maven repository.

# To use

```xml
<repositories>
    <repository>
      <id>rchemist.invesdwin.mirror</id>
      <url>https://github.com/rchemist/release-invesdwin-instrument/raw/main/releases</url>
    </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>de.invesdwin</groupId>
    <artifactId>invesdwin-instrument</artifactId>
    <version>1.0.14</version>
  </dependency>
</dependencies>
```

# Have fun!