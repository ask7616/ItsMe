# It's Me Project

***인천대학교 / 캡스톤디자인(1) / 이 승수 교수님 / 1병근2성균 팀***

### 진행상황
* 커스텀 데이터 학습 모듈 구현
* 객체 추척 및 카운팅 모델 구현
* EC2 <-> 라즈베리파이 간 통신 서버 (작업 중)

##### 1. 가상환경 세팅
~~~
conda create -n py38 python=3.8    
conda activate py38
~~~
~~~
pip install -r requirements.txt
~~~

##### 2. PyTorch 설치
conda
~~~
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
~~~
pip는 https://pytorch.org/get-started/locally/ 에서 실행코드 복사하기
![image](https://github.com/ask7616/ItsMe/assets/68906169/6e648d4b-e54b-4d43-9237-35520c47548f)

##### 3. 실행방법
~~~
python main.py --cam 0 --display
~~~

##### 
