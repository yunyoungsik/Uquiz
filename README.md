# Uquiz
<img width="100%" src="https://github.com/yunyoungsik/Uquiz/blob/main/assets/img/thumbnail.jpg?raw=true" />
U.QUIZ라는 퀴즈 웹 애플리케이션을 위한 초기 레이아웃과 로직을 포함하고 있습니다.<br/>
이 웹사이트는 이미지 퀴즈를 풀며 사용자의 정답 여부를 확인하고, 타이머를 통해 제한 시간 내에 문제를 푸는 기능을 제공합니다.<br />

## 사용된 기술
- 배경 이미지 처리
body와 .wrap 요소에 각각 배경 이미지를 적용하여 페이지와 콘텐츠의 배경을 꾸몄습니다.<br />
background-image, background-position, background-size 등을 사용하여 배경 이미지의 표시 방식을 조정했습니다.<br />
   
- DOM 요소 선택과 이벤트 처리
document.querySelector를 사용하여 HTML 요소를 선택하고, 해당 요소에 대한 이벤트 리스너를 추가하여 상호작용을 구현했습니다.<br />
예를 들어, 모달 닫기 버튼에 클릭 이벤트를 추가하여 모달 창을 닫거나, 정답 확인 버튼과 다음 문제 버튼에 이벤트를 할당하여 상호작용하도록 만들었습니다.<br />

- 반복적인 기능을 위한 배열과 함수 활용
quizInfo 배열을 사용하여 문제와 정답 이미지의 경로를 담았습니다.<br />
shuffleArray 함수를 만들어 배열을 무작위로 섞는 기능을 구현했습니다.<br />

- 문제 출력과 정답 확인
updateQuiz 함수를 사용하여 현재 문제를 화면에 출력했습니다.<br />
사용자가 입력한 답과 정답을 비교하는 checkAnswer 함수를 만들어 사용자의 입력에 따라 알맞은 결과를 표시했습니다.<br />

- 타이머 기능
startTimer 함수를 사용하여 제한 시간 내에 사용자가 퀴즈를 푸는 기능을 추가했습니다.<br />
setInterval을 활용하여 일정 시간 간격으로 타이머를 업데이트하고, 시간이 초과되면 사용자에게 알림을 표시하는 방식으로 구현했습니다.<br />
