# OSS Personal Project Phase1 : Wordle
## 구현 목표
#### 프로젝트의 목표는 유명한 게임인 Wordle을 Pygame으로 구현하는 것이다. 
#### Wordle은 숫자 야구처럼 시작 시 무작위하게 정답 단어가 결정이 되고, 플레이어는 해당 단어를 추측하는 게임이다. 숫자 야구와 비슷하게, 각 추측마다 색깔을 통해 정보를 제공한다. 각 추측에 있는 철자마다 정답 단어에 존재하지 않으면 회색, 존재하지만 위치(Index)가 다르면 노란색, 존재하는 위치까지 같으면 초록색으로 나타내어준다. 
#### 총 6번의 추측기회가 주어지며 6회 이내에 맞추면 승리, 6회 이내에 맞추지 못하면 패배이다.

## 구현 기능
- pygame 기반 Game Screen 구현
- 키보드 입력을 통한 단어 추측
- 단어 추측시 색깔을 통해 정보 제공
- HINT 기능을 만들어 HINT 칸을 누르면 무작위하게 한 글자의 정보 제공

## Reference
[1] <https://github.com/pygame/pygame> "pygame"

## 지원 OS 및 실행 방법
### 지원 OS
|OS| 지원 여부|
|-----|-------|
|Windows| :o: |
| Linux | :o: |
| MacOS | :x: |
### 실행 방법
#### Windows
1. python3.12를 설치한다.
2. swig을 설치한다.

## 실행 예시

## 코드 설명

### wordle.py
#### class Tile

#### class Letter

#### class Keyboard

#### def create\_letter()

#### def delete\_letter()

#### def guess\_check(guessed\_word)

####  

