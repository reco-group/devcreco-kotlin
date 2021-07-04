# 코틀린 공유 영상





## 코틀린 1강 제가 직접 한번 돌려 보도록 하겠습니다

[![코틀린 1강 제가 직접 한번 돌려 보도록 하겠습니다](https://i.ytimg.com/vi/aUd3dQNrm2s/hqdefault.jpg?sqp=-oaymwEZCNACELwBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLCdoqm7bF0s8JpEDZmqjDNwqvaoBQ)](https://youtu.be/aUd3dQNrm2s)

```bash
kotlinc -script hello.kts


# Tip

Kotlin은 jdk 8 까지 제대로 library를 불러올 수 있는 것 같다.

### mac에서 jdk 8 설치하는법 (sdkman을 활용)

```bash
sdk list java
sdk install java 8.0.212-zulu
```
### mac에서 여러 jdk 사용하는법

```bash
sdk install java 8.0.212-zulu
sdk install java 12.0.1.j9-adpt

# 임시 변경
sdk use java 11.0.1-zulu

# 지속 변경
sdk default java 11.0.1-zulu 
```
