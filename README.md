
How to use
  
1. cyclictest_scripts.sh에서 가능한 백그라운드 테스트 목록의 인덱스를 이용해 cyclictest with stress test할 test를 순서대로 배열에 저장해줍니다.

2. stress test는 10분(=600s)으로 설정되어있습니다. 원하는 시간이 있다면 time 변수값을 변경합니다.

3. call_cyclictest 함수에서 cyclictest의 옵션을 바꿀 수 있습니다.

4. cmd상에서 cyclictest_scripts.sh가 있는 폴더에서 명령어로 ./cyclictest_scripts.sh를 입력하여 실행합니다.

5. 모든 test가 끝나고나면 test.txt 파일에 각 test의 core 당 max latencies와 그 중에서 가장 높은 latency를 보여줍니다.
