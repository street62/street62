<div align='center'>

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=300&section=header&text=Senglee%20Choi%27s&fontSize=70&animation=fadeIn)

![Senglee Choi's Github Stats](https://github-readme-stats.vercel.app/api?username=street62&hide=stars&count_private=true)
    
안녕하세요.

**늘 'why'를 고민하는 개발자** 최승리입니다.
    
</div>




## Projects
### [집넘기기](https://github.com/jminie-o8o/Home-Rent-App)
- 임시로 집을 구하는 사람들을 위한 매물 중계 앱입니다.
- 스프링 부트 기반 서버 어플리케이션을 백엔드 2인 팀으로 개발했습니다.
- Junit + Mockito를 이용한 단위 테스트 및 RestAssured를 사용한 API 테스트를 수행했습니다. API 테스트 진행 중 임베디드 DB를 사용함에 있어서 생기는 문제점을 발견하고 해결한 경험이 있습니다. (https://keepseeking.tistory.com/20)
- nGrinder를 활용한 성능 테스트를 진행하면서 ORDER BY로 정렬하는 DB 쿼리에서 성능 저하가 나타남을 확인하고, 정렬 대상 컬럼을 포함한 복합 인덱스를 사용해 정렬 연산의 오버헤드를 줄인 경험이 있습니다.



### [issue-tracker](https://github.com/jminie-o8o/issue-tracker)
- 이슈/마일스톤 관리 프로젝트입니다.
- JWT 토큰과 Oauth를 사용한 소셜 로그인 기능을 구현했으며, 해당 기능을 구현하면서 Oauth 서비스에 따라 다형적으로 동작하는 객체지향적 코드를 작성하는 데에 집중했습니다.
- 로그인 구현 과정에서 자바의 Optional을 사용하면서, orElse()와 orElseGet() 메서드의 차이 때문에 발생했던 문제점을 발견하고 이를 해결한 경험이 있습니다. 단순히 문제 해결 뿐만 아니라, 메서드의 구현을 살펴보며 함수형 인터페이스가 기존 자바가 가지고 있던 한계점들을 어떻게 보완하고 있는지 탐구해 보았습니다. (https://keepseeking.tistory.com/15)



## Blog
**[티스토리 블로그: Keep Seeking](https://keepseeking.tistory.com/)**

학습하고 프로그래밍하는 과정에서 부딪힌 여러 궁금증들을 글로 풀어내고 있습니다. 정답을 찾기보다는 문제를 해결해 나가는 과정을 돌아보고, '왜 필요할까, 왜 이렇게 동작할까' 질문을 던지며 기술에 대한 이해를 높이고자 노력합니다.

- [눈 씻고 로그인 로직 버그 찾기](https://keepseeking.tistory.com/15): 로그인 로직 구현 중 자바의 Optional과 관련해 발생한 문제를 돌아본 글입니다. 문제의 원인이었던 `orElse()`와 `orElseGet()`의 차이뿐만 아니라, 그 속에 있는 함수형 인터페이스의 작동 원리와 필요성에 대해 고민해 보았습니다.
- [백만 개 Row를 수정하다가 트랜잭션을 롤백한다면?](https://keepseeking.tistory.com/18): 매우 큰 규모의 트랜잭션을 롤백해야 할 때, DBMS 별로 트랜잭션의 ACID를 구현하기 위해 선택한 설계 방식과 장단점에 대해 탐구한 글입니다.
- [해시테이블 하나에 담긴 고민들](https://keepseeking.tistory.com/19): 자바의 LinkedHashMap과 파이썬의 Dictionary의 내부 구조를 살펴보면서, 더 효율적으로 동작하는 자료구조를 구현하기 위한 언어 설계 과정에서의 의사결정과 문제 해결 과정을 분석한 글입니다.
- [외계어 같은 Git 메시지들을 이해해 보자](https://keepseeking.tistory.com/17): Git을 통해 add, commit, push를 진행하는 과정에서 등장하는 CLI 상의 메시지들을 분석하며, git이 내부적으로 어떤 구조를 통해 코드를 저장하고 변경사항을 추적하는지 풀어낸  글입니다.
- [그래서 다익스트라는 얼마나 걸리는 거예요?](https://keepseeking.tistory.com/14): 다익스트라 알고리즘의 시간복잡도를 다익스트라의 여러 구현 방식에 따라 분석한 글입니다.
- [뭔지는 알고 쓰자 WebClient!](https://keepseeking.tistory.com/13): 코드 리뷰 시에 WebClient 사용에 대해 받았던 피드백에서 출발해 RestTemplate과의 차이점과, 동기식 MVC 구조에서 WebClient를 사용할 때에 고려할 점에 대해 정리했습니다.

## Experience
- 카카오뱅크 테크인턴 2기 (2023.01.02 ~ 2023.03.03)

## Education
- 코드스쿼드 2022 마스터즈 백엔드
- 연세대학교 언론홍보영상학부 졸업


## Etc.
- [알고리즘 풀이 Notion](https://psychedelic-turquoise-a2a.notion.site/31689a227add42d8b8a3a2e6b558e499): 알고리즘 문제를 풀면서 저의 접근 방식과 다른 코드들의 접근 방식을 비교하면서 학습하고 정리하고 있습니다.






<!--
**street62/street62** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
