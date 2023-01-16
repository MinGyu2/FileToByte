## 파일 바이트 로 나타내기

목표: java 를 이용하여 리눅스 처럼 파일을 바이트로 읽어낸다

### 순서
 1.  자바의 FileReader(~) 클래스를 이용하여 파일을 읽는다. 
 2.  16 byte 로 쪼개어 보여준다.
 3.  리눅스의 xxd 명령어와 같은 형태로 정리한다.

### 예상 동작 화면
![Pasted image 20230116124202](https://user-images.githubusercontent.com/31990118/212647141-6cdd8605-3afa-4cec-b12a-03643b9d5763.png)
출처:  [Working with Magic numbers in Linux - GeeksforGeeks](https://www.geeksforgeeks.org/working-with-magic-numbers-in-linux/)

### 동작 화면
 ![Pasted image 20230116183519](https://user-images.githubusercontent.com/31990118/212647227-1f385ced-1d8d-4bf1-a5ff-de5dba0a6bdc.png)



개발 ide
	vscode

개발 언어
	java

참고 사이트
 - https://hianna.tistory.com/587
 - [Working with Magic numbers in Linux - GeeksforGeeks](https://www.geeksforgeeks.org/working-with-magic-numbers-in-linux/)
 - [[JAVA] JAVA의 입출력, 바이트 스트림(ByteStream) | Yoon's Dev (tistory.com)](https://yooniron.tistory.com/17)