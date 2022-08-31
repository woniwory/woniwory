### I don't know anything about OOP 🤔
### ROK Army CERT ⚡(2022.05.16 ~ 2023. 11.16) 
- I’m currently working on InfoSec and Monitoring 😄
<!--
**woniwory/woniwory** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
https://www.bezkoder.com/react-spring-boot-crud/

조건
파라매트릭 서치는 굉장히 강력한 문제 해결 도구지만, 안타깝게도 모든 문제에 적용할 수는 없고, 아래 세 조건을 만족하는 문제에만 활용할 수 있다.

특정 조건을 만족하는 최댓값/최솟값을 구하는 형식의 문제여야 한다. 혹은 이러한 형태로 변형이 가능해야 한다. 예를 들어 위의 고기의 경우에도, “200g이하의 고기 중 최댓값을 구하여라”라는 문제로 생각할 수 있다.
최댓값을 구하는 문제의 경우 어떤 값이 조건을 만족하면 그 값보다 작은 값은 모두 조건을 만족해야 한다.(최솟값의 경우 그 값보다 큰 값은 모두 조건을 만족해야 한다.) 그래야 조건을 만족하는 경우 더 큰 값을, 만족하지 않는 경우 더 작은 값을 확인하면서 이분탐색을 통해 답을 구할 수 있다.
답의 범위가 이산적이거나(e.g. 정수) 허용 오차 범위가 있어야 한다. 이분탐색으로는 연속적인 범위에서 정답에 한없이 가까워질 수는 있지만 완전히 정확한 값은 구할 수 없기 때문에다.


woniwory/README

Strategy : 문제를 단편화해서 하나씩 쉽게 체계적으로 접근하자.
단편화한 곳 중 난이도를 가르는 곳은 어디일까


parametric search로의 확장 :

중요포인트 : 연속적이고, 이산적 -> 정렬되어있고, 정수이다
최적화와 결정 -> 종료조건

이진탐색을 두 번.

파라메트릭 서치(Parametric Search)
매개 변수를 이용한 탐색 기법
최적화 문제를 결정 알고리즘을 사용하여 해결
결정 알고리즘은 이진 탐색을 사용
결정 알고리즘은 원소의 나열 안에 구하고자 하는 답이 존재하는 경우 사용


문제 풀이 아이디어 : 구하고자하는 답(answer)을 반복해서 조정
즉, 구하고자 하는 답(answer)는 반복문 안에서 계속해서 변경된다.
구하고자하는 답(answer)은 반복문안에서 계속해서 변경되는 중간점(middlePoint)를 의미한다.
즉, 결정 알고리즘에서는 최종적으로 middlePoint 가 answer 가 된다.


단순 이진 탐색 구현과의 차이점
함수를 사용한다.
결정 알고리즘에서 시작점(startPoint) : 입력 값 n 의 시작 범위 (1 <= n <= 10000 이므로 1)
결정 알고리즘에서 끝점(endPoint) : 배열의 마지막 원소 값(arr[n-1])
반복문이 끝난 middlePoint 가 answer 가 된다.




start end mid result
4 46 40
4 26 4
26 26 26
26 4 4
-->
