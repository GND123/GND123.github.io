---
layout: post
title: 깃허브 업로드 하는 방법
---

***
1.  깃 저장소를 초기화한다. 이미 연결하려고 하는 깃repo가 있다면 두 번째 명령어를 실행한다.
~~~
git init
git clone https://github.com/GND123/gnd123.github.io.git
~~~

2. 깃 local에 변경할 파일을 추가한다.
~~~
git add fileName
~~~

3. git local에 커밋한다.
~~~
git commit -m "commit-message"
~~~

4. git init을 썻을 경우 github repo와 연결시킨다.
~~~
git remote add origin https://github.com/GND123/gnd123.github.io.git
~~~

5. github에 push한다.
~~~
git push origin master
~~~
