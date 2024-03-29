# 쉬운 넌센스&구데기 문제집 Ver. 1.22474487139... Editorial

## 들어가기 앞서

문제집 주소 : https://www.acmicpc.net/workbook/view/11718

이 문제집은 하라는 DFS와 BFS와 DP는 안 하고 번외 문제와 구데기컵 문제에 심취한 한 유사 PS러가 만든 문제집입니다. 정작 첫 구데기컵 참가는 2022년입니다.

제가 문제의 출제자가 아닌데도 불구하고 있는 문제를 모아다가 문제집을 만든 것인지라 "에디토리얼" 이라는 단어를 붙이는게 맞나 싶었지만, 일단 제가 문제집을 만들었고 그 문제집을 만든 나름의 이유 또는 최소한의 힌트, 약간의 여담 등을 쓰는 것이 맞다는 판단하에 문제집에 대한 에디토리얼이라는 단어를 일단 사용하였습니다. 만약 다른 용어가 더 적절하다고 생각되시는 경우, 그 즉시 알려주시면 감사하겠습니다.

이 문제집에는 두 가지의 이스터에그를 넣었습니다.

하나는 ***Ver. 1.22474487139...*** 로, 니어 레플리칸트 개선판 이름인 "NieR Replicant ver.1.22474487139..." 에서 따왔습니다. 문제집이 업데이트 되어도 버전업은 없습니다.

다른 하나는 문제집 설명 칸에 있는 ***I'll leave you to Googling.*** 으로, 히트맨 시리즈의 다이애나 번우드의 유명한 대사인 "I'll leave you to prepare, 47." 에서 따왔습니다.

제출 즉시 정답의 여부가 달라질 수 있는 문제 또는 매일 답이 바뀌는 문제들은 일부러 넣지 않았습니다. 랜덤~~갸차~~을 싫어하는 저의 지극한 주관에 따른 것입니다. [15641번 문제](https://www.acmicpc.net/problem/15641), [17113번 문제](https://www.acmicpc.net/problem/17113), [24904번 문제](https://www.acmicpc.net/problem/24904)와 [24905번 문제](https://www.acmicpc.net/problem/24905)가 대표적인 예시라 보시면 되겠습니다. 푸는 방법은 쉽기에 쫄지 않아도 됩니다. [2555번 문제](https://www.acmicpc.net/problem/2555)는 넣지 않았는데, 답이 한 번 바뀐 이후로 순수 랜덤 문제가 되어버렸습니다.

**아래에서도 말씀을 한 번 더 드릴 예정이지만, 모든 구데기컵 문제의 설명은 구데기컵 에디토리얼을 어느정도 차용했음을 밝힙니다.** 구데기스러운 문제를 계속 만들어주시는 [주식회사 구대기](https://github.com/ghudegy) 출제자분들에게 항상 감사드립니다.

이 곳에서는 푸는 재미를 극대화하기 위해서 최소한의 정보만을 제공합니다. 많이 알려진 문제라면 적당한 수준에서 정보를 제공합니다. 문제집이 문제집이다보니 문제집 제작자도 글의 수준이 낮을 가능성이 있습니다만 그러려니 해주시기 바랍니다.

문제집 설명 칸에 있는 설명을 토대로, 이 문제들은 **구글링을 적극 장려하는 문제집**이라는 것을 알 수 있습니다.

이 문제집에서 정의한 "쉬운" 의 정의는 푸는 방법 자체가 쉬운 것, 그리고 구글링 난이도가 낮은 것으로 정하였습니다.

노가다의 정도는 문제마다 다르며, 이것으로 푸는 난이도를 정하지는 않았습니다. 이거까지 고려를 하면 빼야할 문제가 몇 개 있지만, 도전심을 자극하기 위해 일부 노가다가 필요한 문제를 넣었습니다.

구글링이 안되는 일부 넌센스 문제의 경우, 알고보면 참 허무할 정도로 쉬운 것만 넣었습니다.

구글링으로 얻은 정답 코드를 절대로 치팅(카피)하지 말아주시기 바랍니다. 모두에게 피해가 됩니다.

앞으로 구데기컵이 계속 열린다거나, 넌센스 문제가 업데이트 되거나, 미처 알지 못한 문제를 발견하거나, 구글링 난이도가 급격히 상승할 시 업데이트 합니다. 문의 환영합니다. 물론 수정되어도 버전업은 없습니다.

문제집이 마음에 드신 경우, 따봉을 눌러주시면 감사하겠습니다. :)

## Q1237 정ㅋ벅ㅋ

매우 유명한 문제입니다. 문제만으로도 답을 구할 수 있으며, 정 모르시겠다면 구글링으로 쉽게 답을 찾을 수 있습니다.

## Q2555 생일 출력하기

백준 사이트의 생일을 출력하면 됩니다. 어디있는지는 직접 찾아보시면 됩니다.

## Q2556 별찍기 - 14

이 또한 매우 유명한 문제입니다. 구글링으로 쉽게 답을 찾을 수 있습니다.

## Q9073 말이 안되는 명대사

이 문제는 질문 검색에 있는 결정적 [힌트](https://www.acmicpc.net/board/view/58364)를 확인하시면 푸는 난이도가 급감합니다.

## Q9987 포켓몬 마스터

구글링 하시면 됩니다.

## Q9995 HM과 TM

구글링 하시면 됩니다.

## Q9999 구구

구글링 하시면 됩니다.

## Q10212 Mystery

구글링 하시면 됩니다.

## Q10889 Ancient symbol

구글링 하시면 됩니다.

## Q11506 占쏙옙

구글링 하시면 됩니다.

## Q12091 이브이 진화 시키기

구글링 하시면 됩니다.

## Q12092 포켓몬 GO 진화

구글링 하시면 됩니다.

## Q12096  

해당 문제의 페이지 소스 보기를 통해 문제를 풀 수 있습니다. 정 모르시겠다면 구글링 하셔도 됩니다.

## Q13131 HicCup

구글링 하시면 됩니다. 지문을 도최 못 읽겠다면 Python의 replace 함수를 이용해서 제거하신 후 보시면 됩니다.

## Q14406 좌중을 사로잡는 건배사

구글링 하시면 됩니다.

## Q15547 Lorem ipsum

먼저 Lorem ipsum의 위키백과 설명은 아래와 같습니다.

    로렘 입숨은 출판이나 그래픽 디자인 분야에서 폰트, 타이포그래피, 레이아웃 같은 그래픽 요소나
    시각적 연출을 보여줄 때 사용하는 표준 채우기 텍스트로, 최종 결과물에 들어가는 실제적인 문장 내용이
    채워지기 전에 시각 디자인 프로젝트 모형의 채움 글로도 이용된다.
   
즉, 이 문제에서의 지문들은 전부 뻘글이란 뜻이며, [Lorem ipsum 제너레이터](https://www.lipsum.com)에서 가져왔을 가능성이 매우 높습니다.

하지만 이 문제의 핵심은 입력과 출력입니다. 그래도 모르시겠다면 맞힌 사람의 코드 길이를 가지고 충분히 유추해볼 수 있습니다.

## Q15629 Africa

전설적인 첫 구데기컵 문제입니다. 비문학 지문 하나 읽는다 치고 풀어봅시다. 국가와 비자 비용, 그리고 비용 조건을 핵심적으로 보는게 중요합니다.

#### [중요] 사실 구데기컵의 거의 모든 풀 수 있는 문제들은 에디토리얼에 답이 존재합니다. 이걸 이용하시면 구데기컵에서 나온 문제는 거의 대부분 날먹이 가능합니다. 구데기컵 문제 중 이 방법으로 풀 수 있다는 말은 계속 중복이 되기에 특수한 경우가 아닌 이상 이 시점 이후로 하지 않습니다. 또한 구데기컵에서 가져온 모든 문제들의 설명은 구데기컵 에디토리얼을 참고하였음을 다시 한 번 더 밝힙니다.

## Q15631 BOJeopardy

이 문제의 목적이 구글링으로 푸는 것입니다.

## Q15636 Linear Algebra and Group

이 문제에서 언급된 선형대수와 군은 서울대에서 출판된 소위 선대군 이라는 유명한 선형대수 교재입니다. 개인적으로 이공계 개그가 많이 있어서 재밌게 본 기억이 납니다. 선형대수를 공부하기엔 나름 괜찮았던 기억 또한 납니다. 만약 선형대수 지식이 필요하다면 추천 할 수 있을 책입니다.

이 책의 표지에 있는 숫자를 전부 합한 값이 정답입니다. 나름 유명해서 구글링을 하면 바로 답이 나옵니다. 무려 유튜브에도 답이 있습니다.

## Q15633 Fan Death

애드블록으로 문단 하나를 가렸던 것이 대회 당시의 핵심이었다고 합니다. ~~지금은 애드블록 있어도 보이는데요?~~

평범한 약수 구하기 문제에 추가로 연산이 하나 더 들어가야 정답입니다.

## Q15637 Lotto

로또 **공식** 사이트의 [회차별 당첨번호](https://dhlottery.co.kr/gameResult.do?method=byWin)를 엑셀로 다운받아 데이터 가공하는 문제입니다.

**공식 사이트의 도메인은 dhlottery 입니다!!! lotto가 아닙니다!!! lotto는 사설 사이트입니다!!! 조심하시길 바랍니다!!!**

크롤링보다는 이게 더 잘 먹힐겁니다.

물론 구글링해서도 정답을 (더 쉽게) 얻을 수 있습니다.

## Q15638 No Description

말 그대로 설명이 없지만, 제 1회 구데기컵 [대회 당시 질문들](https://www.acmicpc.net/contest/qna/278)을 통해서 충분히 답을 유추할 수 있습니다.

결정적 질문이 하나 존재합니다.

## Q15639 Rick

해외에서는 너무나도 유명한 (어쩌면 한국에서도 나름 알려져있는) 밈인 [***RICKROLLING***](https://ko.wikipedia.org/wiki/%EB%A6%AD%EB%A1%A4%EB%A7%81)을 가지고 만든 문제입니다.

하이라이트 부분의 가사에서 "Never gonna" 가 나온 이후의 무언가들이 존재하는데, 그것들이 릭이 하지 않는 행동입니다.

## Q15643 Yee

이 또한 매우 유명한 밈인 유명한 [***Yee***](https://ko.wikipedia.org/wiki/Yee)을 가지고 만든 문제입니다.

문제를 보면 유튜브로 올라온 Yee 영상이 있는데, 듣다보면 어느 한 순간 음악이 멈춥니다. 그 때 영상을 확인해보시기 바랍니다.

Ba ba ba / ba, ba, / ba ba, / baa, ba ba / Ba ba ba / ba, ba, ba ba / Yee

## Q15802 타노스

블립을 통해 5년을 더 젊게 살고 싶다면 0을, 싫다면 1을 출력하세요!

물론 이거 때문에 사람이 사라지진 ㅇ

## Q15890 전국 대학생 프로그래밍 대회 동아리 연합 여름 대회 2018

구글링 하시면 됩니다.

## Q15891 스타트링크 사무실을 파헤쳐보자

구글링 하시면 됩니다.

## Q16647 Happy Birthday, kipa00!

구글링 하시면 됩니다.

## Q17106 빙고

정석적인 풀이는 꽤 까다롭습니다. 괜히 플래4 문제가 아닙니다.

## Q17107 Thinking Language

[Huh?](https://esolangs.org/wiki/Huh%3F)라는 난해한 프로그래밍 언어로 푸는 문제입니다. 물론 구글링으로도 답을 구할 수 있습니다.

입력으로 주어진 지문은 해외에서 유명한 밈인 [꿀벌 대소동](https://en.wikipedia.org/wiki/Bee_Movie)입니다. 나름 인터넷 망령이라 생각했는데 몰랐던 밈이었습니다. 반성하게 됩니다.

## Q17109 연결그래프의 모든 간선의 저항이 1Ω일 경우 간선으로 직접 이어진 모든 쌍의 점 A, B 에 대해 A와 B 사이의 합성저항 값의 총합을 구한 뒤 소수점 넷째자리에서 반올림한 값을 출력하는 문제

회로이론을 진짜 1도 몰라서 구데기컵 에디토리얼을 확인해주시면 되겠습니다.

## Q17116 목격자

예시 입력을 다 처리하면 됩니다.

## Q17117 평가

이례적으로 답을 알려드립니다. 0을 출력하면 됩니다. 사실 구데기컵 에디토리얼에도 나와있어서 큰 문제는 없을 것으로 사료됩니다.

제가 이 정답에 대한 정답 접근 방법이 맞는지 틀린건지 몰라 이렇게 적어봅니다.

먼저 절대/상대 오차가 10-6, 즉 4 이내면 됩니다.

일단 절대 오차 계산법은 (실제 정답 - 내가 쓴 정답) 인데, 이는 예시 1번에 위반됩니다. 따라서 상대 오차로 접근을 해봅니다.

상대 오차 계산법이 ((실제 정답 - 내가 쓴 정답) / (실제 정답)) 입니다.

따라서 모든 정답에 0을 써도 4 안에 들어갑니다. (계산법에 따른 최댓값이 1이고, %가 안 붙기 때문에 100을 곱할 필요가 없음)

그래서 모든 정답에 0을 써도 된다가 성립하는거 같다고 판단했습니다.

논의 환영합니다.

## Q16017 총알의 속도

속도를 구하는 간단한 문제입니다. 다만 시대가 현대임을 아주 많이 감안해야 풀 수 있습니다.

## Q18821 홀수와 짝수의 대결

유명한 다이아5 문제입니다. [포여 추측](https://en.wikipedia.org/wiki/P%C3%B3lya_conjecture)을 이용하는 문제인데, 이걸 알고 푸신 분이 계실까 싶기도...

숫자가 매우 커서 (10억) 미리 전처리를 돌린 후에 코드를 짜야합니다. 아니면 구글링...

## Q18822 Beginning the Hunt

제 1회 구데기컵 문제와 관련된 그림들입니다.

## Q21293 No Description 2

얼마나 틀리는 것에 두려워하지 않느냐에 따라 빨리 풀리는 문제입니다.

## Q21294 와 쿼리

업데이트는 continue, 출력은 빈 줄입니다.

## Q21299 진짜 최종 구데기컵 1 경품 당첨자

진정한 노가다 문제입니다. 다행히 현재는 EtvycAuRLZpb6hhe86x0가 끝난지 오래되어 에디토리얼이 존재하며, 이를 토대로 쓸 수 있는 답을 작성해봅시다.

추천하는 것은 Python 기준 딕셔너리 입니다. input을 key, 나머지 3개를 value list로 잡고 풀면 출력할 때 편합니다.

다만 모든 정답을 다 알려주진 않았습니다. 쉽게 추측해서 찾을 수 있는 답도 있고, 엄청난 노가다를 해야하는 답도 존재합니다.

이 때 약간의 편법으로, floor(맞은 개수/3)에 의해 점수가 바뀌는 것을 이용합니다.

즉, 에디토리얼과 쉽게 추측 가능한 답들을 다 적은 후에, 확실한 정답 개수를 (3의 배수 - 1)개로 줄인 이후 모르는 부분을 하나씩 때려맞춥니다.

맞으면 점수가 상승할 것이고, 틀리면 점수 변동이 없을 것입니다. 그렇게 노가다를 하면서 답을 채우면 풀 수 있습니다.

노가다가 오래 걸리지만 난이도 자체는 어렵지 않았기에 "쉬운" 기준에 적합하다고 판단, 문제집에 넣었습니다.

## Q24900 한별 찍기

그대로 복붙하면 됩니다. 여백까지 다 넣어야합니다.

한별이 귀여워

## Q24907 문제 이름

정말 골 때리는 문제입니다. 당시 풀었던 입장으로 그저 막막했는데요, 그래도 풀었습니다.

원래 풀이법은 이 문제에 적혀진 분의 인적사항을 육군 훈련소 홈페이지에서 찾고, 인편 제목을 보고 첫 단어를 때려맞추는 겁니다.

다만 지금은 시간이 많이 지났기에 육군 훈련소 인편 DB가 사라졌을 가능성이 존재하여 정석적인 방법으로 풀기엔 시간이 지날수록 어렵습니다.

에디토리얼을 참고하시거나, 순전한 운빨 시험을 해보셔도 됩니다.
