---
title: E dpkg was interrupted, you must manually run 'sudo dpkg --configure -a' to correct the problem 해결방법
date:   2022-07-18 16:22:10 +0900
categories: [Tech, Ubuntu]
tags: [linux, server]
---

![error massage](https://user-images.githubusercontent.com/85277660/210788673-5f78eb93-4544-4e39-a8f5-76a14800434c.png)

장고와 MySQL을 연결하기 위해서 패키지가 하나 필요해서 설치를 할려고 하는데 위와 같은 에러가 나왔다.

```
E: dpkg was interrupted, you must manually run 'sudo dpkg --configure -a' to correct the problem.
```

일단 그대로 매뉴얼대로 "<"sudo dpkg --configure -a">"를 입력하고 다시 설치 명령어를 쳤다.

