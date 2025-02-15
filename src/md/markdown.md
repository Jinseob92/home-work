# 마크다운 문법
마크다운이란 ? 
Mark down은 텍스트 기반의 마크업 언어로 2004년 존 그루버에 의해 만들어졌다.
쉽게 쓰고 읽을 수 있다는 장점이 있으며 Html로 변환이 가능하다.
특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 
컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다. 
마크다운이 최근 각광받기 시작한 이유는 Github 덕분이다.
Git hub의 저장소 Repository에 관한 정보를 기록하는 README.md는 Git hub를 사용하는
살마이라면 누구나 가장 먼저 접하게 되는 마크다운 문서이다. 
마크다운을 통하여 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수
있다는 강점이 부각되면서 점점 여러 곳으로 퍼져가게 된다.

간단하게 정리하면 마크다운은 사실상 모든 문서를 서식 지정하는 데 사용할 수 있는 간단하고 사용하기 쉬운 마크업 언어이다.

다른 편집기 대신 마크다운을 사용하는 이유로는 마크다운은 모든 것에 사용할 수 있기 때문이다. 웹 사이트, 문서, 노트, 책,
프레젠테이션, 이메일 메시지, 기술 문서 등에 사용될 수 있기 때문이다. 

마크다운의 장-단점
장점으로는 
1. 간결하다.
2. 별도의 도구없이 작성가능하다.
3. 다양한 형태로 변환이 가능하다.
4. 텍스트로 저장되기 때문에 용량이 적어 보관이 용이하다.
5. 텍스트 파일이기 때문에 버전 관리 시스템을 이용하여 변경이력을 관리할 수 있다.
6. 지원하는 프로그램과 플랫폼이 다양하다.

단점으로는
1. 표준이 없다.
2. 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다.
3. 모든 HTML 마크업을 대신하지 못한다.

마크 다운의 문법으로는 
1. 제목
#을 사용해 제목을 만들 수 있다. #의 개수로 제목의 레벨을 정할 수 있다.
예시) 
# 제목 1 ( 주 제목)
## 제목 2 
### 제목 3 

2. 강조
- 기울임꼴은 텍스트 앞뒤에 *또는 _을 한 개씩 붙여서 작성한다.
- 굵게는 *또는 _을 두 개씩 붙여서 작성한다.
예시) 기울임꼴
*기울임꼴* , _기울임꼴_
예시 ) 굵게
**굵게** __굵게__
예시) 기울임꼴 + 굵게
***기울임꼴과 굵게*** , ___기울임꼴과 굵게___

3. 목록
순서 없는 목록은 -, +, * 중 하나로 시작한다.
순서 있는 목록은 숫자 뒤에 .을 붙여서 작성한다.
예시)
- 아이템 1
- 아이템 2
  - 하위 아이템 1
  - 하위 아이템 2
  1. 첫 번째
  2. 두 번째

4. 링크
링크는 [링크텍스트](URL) 형식으로 작성한다.
예시) [네이버](www.naver.com)

5. 이미지
이미지는 링크와 비슷하게 [이지미 설명](이미지URL)을 사용하지만, 앞에 !을 추가한다.
예시) ![예시 이미지](ex-image)

6. 인용문
인용문은 >을 사용한다.
예시) > "인용문 입니다."

7. 코드
한 줄 코드는 텍스트 앞 뒤에 `을 사용한다.
여러 줄 코드는 ``` 을 세 번 사용하여 코드 블록을 만든다.
예시) `printf("Hello World");
예시) ```printf("Hello like");
       printf("Hello lion"); ```

8. 수평선
수평선은 ---을 세 번 이상 연속으로 입력한다.

9. 테이블
테이블은 |와 - 을 사용해 작성한다.
예시) |------||-----|

출처 : https://gist.github.com/ihoneymon/652be052a0727ad59601
출처 : https://www.markdownguide.org/