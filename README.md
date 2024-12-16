## 블록깨기 게임 구현
1. 블록이 깨지면 20% 확률로 아이템이 떨어진다.(아이템은 빨간색 혹은 파란색 공 중 랜덤)
2. 기존에 회색벽 블록에서 부딪히면 빨간색, 주황색, 노란색 순으로 색깔이 변경(여러번 부딪혀야 깨짐)
3. 모든 블록을 Life가 1이상일 때 깨면 성공, 모든 블록을 깨기전에 Life가 0이 되면 게임 종료

### 구현 상세 설명
#### Item Drop(#1)
- 블록이 깨졌을 떄 20%의 확률로 파란색 또는 빨간색 공이 랜덤하게 떨어진다.
![image](https://github.com/user-attachments/assets/5a1415d4-cc44-4505-bcf4-f7900baa9fa0)


#### Strong Block(#2)
- 처음 기본 색깔은 회색 블록이지만, 충돌을 반복할수록 빨간색, 주황색, 노란색 순으로 색깔이 변화한다.
- 노란색 벽인 상태에서 부딪히면 블록이 사라진다.
![image](https://github.com/user-attachments/assets/726f3645-959c-41a0-ad9c-1435467dd028)
![image](https://github.com/user-attachments/assets/64af4c4a-54ac-4804-9b48-a6dd7e72e6cb)

### Contributor
- https://github.com/conradrado/OSS_Project2_contributor
