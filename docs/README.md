# 🌉 다리 건너기 게임

다리 건너기 게임은 플레이어가 자동으로 생성할 다리 길이 3이상 20 이하의 숫자를 먼저 입력받는다.  
라운드마다 플레이어는 이동할 칸을 U(위 칸) 또는 D(아래 칸) 중 하나의 문자를 입력한다.  
매 라운드마다 플레이어가 맞추면 다음 다리로 건너가고 이동할 수 없는 칸을 선택하게 되는 경우에는 게임 재시도 또는 종료 중 하나를 선택한다.  
모든 이동할 수 있는 칸을 선택하거나 게임 종료를 선택하는 경우에 최종 게임 결과가 나오며 총 시도한 횟수가 출력된다.

## ✏️ 기능 목록

* 게임을 시작하는 문구와 입력 문구를 출력 후 다리의 길이를 입력 받는다. ✔️
    * 숫자 의외의 입력이 들어오면 예외처리 한다. ✔️
    * 길이가 3부터 20 사이의 숫자가 아니면 예외처리 한다. ✔️


* 다리의 길이만큼 무작위로 위(U) 아래로(D) 건널 수 있는 칸과 없는 칸으로 이루어진 다리를 생성한다. ✔️


* 각 라운드마다 이동할 칸을 입력 받는다. ✔️
    * "U" 또는 "D" 외의 문자가 입력될 경우 예외처리 한다. ✔️


* 플레이어가 이동할 수 있는 칸을 선택하고 아직 선택이 남은 경우: ✔️
    * ``` [ O ] ``` 를 진행 해왔던 칸에 붙여 다시 입력 받는다. ✔️


* 플레이어가 이동할 수 없는 칸을 선택하는 경우: ✔️
    * ``` [ X ] ``` 를 진행 해왔던 칸에 붙여 출력하고 게임 재시도 여부를 입력 받는다. ✔️
    * 재시도 여부는 재시작 "R" 또는 게임 종료 "Q"를 입렵 받는다. 이 외의 문자를 입력하는 경우 예외처리 한다. ✔️
    * "Q"를 입력받는 경우 최종 게임 결과, 게임 성공 여부, 총 시도한 횟수를 출력하고 종료한다. ✔️
    * "R"를 입력받는 경우 생성된 다리는 그대로, 게임을 처음부터 다시 시작한다. ✔️


* 플레이어가 모든 이동할 수 있는 칸을 선택하면 최종 게임 결과, 게임 성공 여부, 총 시도한 횟수를 출력하고 종료한다. ✔️