# 실행파일
실행파일은 드라이브에서 다운로드: https://drive.google.com/drive/folders/13AuEXjVmTF_Fwd8IrAGHmuj9F_URFSOn?usp=sharing

# path 설정
이미지들: ./img/groupname/######.jpg (e.g., ./img/tshirt/000001.jpg)


아웃풋: ./Output/groupname/######.jpg (e.g., ./Output/tshirt/000001.json) (자동생성됨)

# img 다운로드
드라이브에서 알집파일 다운로드: https://drive.google.com/drive/folders/1K5yxXR2ZKOG1P75smlirVb75QlScP1od?usp=sharing

Labeling 현황표는: https://docs.google.com/spreadsheets/d/1KaKaeOg3LoAzql_bX-4tHDzZT0G--1ydIJaYgP4DugE/edit#gid=0

# 키
(이미지 화면에서)
1. 마우스 클릭: 랜드마크를 차례대로 클릭 (티 앞면: front.png, 티 뒷면: back.png 참고)
2. f: 티 앞면 랜드마크를 모두 선택하였을 경우
3. b: 티 뒷면 랜드마크를 모두 선택하였을 경우
4. c: 티 사진이 적절하지 않은 경우 (가려져 있거나, 티가 2개 이상이거나, 카라티셔츠이거나, 긴팔티셔츠이거나, 등등)
5. d: 레이블링을 그만하려는 경우 (나중에 이어서 할 수 있음)
6. r: 다시 레이블링 하기

# 주의사항
1. 폴더 이름이 영어이어야 하므로, 한글 데이터 폴더는 영어로 바꾼 후에 다시 한글로 바꿔서 업로드해야한다...
2. front에서 12번은 팔과 몸통이 만나는 겨드랑이 부분, 7은 어깨선
3. Labeling을 동시에 하면 겹치는 불상사가 발생할 수 있으니 꼭 Labeling 현황표를 참고합시다.
4. 레이블링이 완료되면 Output에 생성된 폴더를 https://drive.google.com/drive/folders/1yRCzOGRWU16mGZ9GF56w08QbUTZ_VmpS?usp=sharing 에 업로드해주세요.

![front.png](./git_images/front.png "front.png")
![back.png](./git_images/back.png "back.png")