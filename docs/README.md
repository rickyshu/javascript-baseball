#프리코스 2주차 기능 구현

- 게임 시작 문구 출력하기

- 게임 시작 문구 후 바로 computer에서 램덤 숫자 생성하기

- 생성 후 player에게 "숫자를 입력해주세요 : " 문구를 띄운 후 입력을 받기!

- 유저가 입력한 숫자를 받아 유효한 값인지 여부를 먼저 판별하기!

  - 의도하지 않은 값을 입력했을 경우 throw Error을 하기 (의지하지 않은 입력값: 3자리 숫자가 아닌 경우 || 3자리가 서로 다른 숫자가 아닌 경우 || 숫자가 아닌 입력값이 들어올 경우)
  - 제대로된 입력을 받았을 경우, 그에 따른, `볼`, `스트라이크`, `낫싱` 결과값을 출력하기
    - 입력된 값의 strike 갯수와 ball 갯수를 계산하는 기능 구현
    - strike와 ball에 갯수에 따라 문구를 출력하는 기능 구현

- player가 램덤으로 생성된 숫자와 동일한 방식으로 숫자를 맞췄을 때 "숫자를 모두 맞히셨습니다! 문구를 띄운 후

  - 게임을 새로 시작: 1, 게임을 완전히 종료: 2 둘 중 하나를 선택할 수 있도록 문구를 띄운다!
  - player의 입력 값에 따라 게임 종료 여부를 결정한다!
