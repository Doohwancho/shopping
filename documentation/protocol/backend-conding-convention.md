# types of linters used


1. checkStyle (intellij plugin)
2. code formatter for java (google style)


## 1. checkStyle


What?

code style이 일정한 규칙에 의해 작성되었는지 알려주는 도구


How?

1. intellij plugin download -> restart ide
2. intellij tab에 연필 모양을 클릭 후 실행하여, 어느 라인에 어떤 문제가 있는지 확인 가능




## 2. code formatter


What?


guide: https://google.github.io/styleguide/javaguide.html


How?


1. preference -> code style -> java -> schema의 톱니바퀴 클릭 -> import schema
2. copy & paste below .xml from the link
	- https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml
3. option + command + l  .. to auto-format a file
4. right click project -> reformat code .. to auto-format an entire project


