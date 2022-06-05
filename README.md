# open-source-software-assignment
리눅스 명령어 top, ps, jobs, kill 설명 &amp; vim 매크로 사용

## top
>실시간으로  cpu 사용률을 체클할 수 있는 명령어

## top 명령어를 입력 후 출력된 화면
![KakaoTalk_20220605_205928185](https://user-images.githubusercontent.com/106912531/172049680-baa21c69-2571-433e-a631-4c018db083d5.png)
>첫 번째 줄은 서버 정보를 담고 있음

>두 번째 줄은 프로세스 정보를 담고 있음

>세 번째 줄은 cpu 정보를 담고 있음

## top 옵션

|옵션|설명|
|---|---|
|– b|배치 모드로 정보를 출력|
|– d <시간>|지정한 시간의 간격으로 정보를 업데이트하여 출력|
|– p <pid>|지정한 프로세스 ID(pid) 정보만을 출력|
|– q|시간의 간격 없이 계속하여 업데이트 정보를 출력|
|– S|누적된 정보를 출력|
