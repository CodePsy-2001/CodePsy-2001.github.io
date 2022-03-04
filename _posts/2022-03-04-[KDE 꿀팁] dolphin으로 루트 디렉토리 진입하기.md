---
title: "[KDE 꿀팁] dolphin으로 루트 디렉토리 진입하기"
date: 2022-03-04 10:14:14 +0900
categories: [프로그래밍, 메모]
tags: [linux, KDE]
---

[![dolphin-f4.png](https://i.postimg.cc/mgdKbtMz/dolphin-f4.png)](https://postimg.cc/Hry6zW6d)

**F4**로 dolphin 파일 탐색기에서 콘솔창을 열 수 있다.



[![dolphin-f4-2.png](https://i.postimg.cc/JhGvtMcT/dolphin-f4-2.png)](https://postimg.cc/McJdFkLR)

```shell
cd /
```

콘솔창에서 디렉토리를 이동하면 dolphin 화면도 같이 따라간다.

그러므로, 콘솔창에서 루트 디렉토리로 이동하면 된다.



또는, 아래 명령을 이용해 현재 디렉토리에서 dolphin을 열 수도 있다.

```shell
dolphin . &
```

이 경우 기존에 켜진 dolphin 세션이 있었으면 '새 창'이 아닌 '새 탭'으로 열리며, 해당 세션에 달라붙는다.

(콘솔창을 꺼도 dolphin이 유지된다.)
