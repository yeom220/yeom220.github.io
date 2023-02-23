---
title: "Mac(Big Sur) rbenv 빌드 실패 이슈 해결방법"
except: "Git Hub 블로그를 위해 rbenv 패키지 설치 중 빌드 실패 해결방법"

categories:
  - Mac
tags:
  - [Mac, ruby, rbenv, issue]
last_modified_at: 2023-02-23
---

github 블로그를 시작하기 위해 rbenv 패키지 빌드 중 에러가 발생했다.  
이슈 로그에는 SSL 버전에 대한 문제처럼 보였다.  
하지만 SSL 1.1 버전을 쓰고 있었고 해당 버전에 대한 이슈를 찾지 못했고
SSL 문제가 아닐수도 있다는 생각이 들어, rbenv 설치 중 발생하는 이슈에 대해 찾다가 해결방법을 발견하였다.    
해결방법이 순서대로 친절하게 잘 정리되어 있으니, 같은 문제를 겪고 있는 경우 시도해보길 바란다.  
[rbenv 빌드 이슈 해결방법](https://gist.github.com/Neutrollized/37841827940b28b27ec2e54abbbcc408)   

