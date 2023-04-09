# CUDA INSTALL METHOD
cuda 사용법과 환경설정 및 토치로 적용어떻게하는지 적어놓았습니다.
```
우선 자신의 그래픽 사양을 알아야하므로 아래 코드를 입력해야합니다.
dxdiag -> 디스플레이에 들어가면 그래픽 사양확인가능
```
![image](https://user-images.githubusercontent.com/97833069/230761945-fb4f4d1b-89be-4eda-b834-9c2898cc05e6.png)</br>
```
그 다음으로 드라이브를 설치해야한다.
```
[드라이브 설치 링크](https://www.nvidia.co.kr/Download/index.aspx?lang=kr)
```
이를 끝났으면 알맞은 버전의 cudnn을 다운받고 파일을 cudatoolkit다운받은 경로에 넣어준다.
다음으로 시스템 환경변수 설정을 해줘야한다. 이를 위해 제어판과 고급설정에 들어가
다음 3개의 시스템변수를 추가해준다.
bin,lib,
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7\bin
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7\lib
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7\include
```
![image](https://user-images.githubusercontent.com/97833069/230768503-fe47bc70-5537-448b-84b7-d214650b7c91.png)
```
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7 보통 경로는 옆과 같다.
또한 계속할거냐고 물어보면 yes 덮어쓰기를 하면된다.
```
![image](https://user-images.githubusercontent.com/97833069/230767005-4fbaa4d3-3c63-406a-bc4f-f208722121c2.png)
```
마지막으로 pytorch 등등을 깔아서 적용하면되는데 버전은 아래 링크에서 확인가능
```
[파이토치링크](https://pytorch.org/get-started/locally/)
