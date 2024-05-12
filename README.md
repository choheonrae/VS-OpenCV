# VS-OpenCV
## opencv설정 과정
### 1.c:\에 Opencv 오픈소스를 저장합니다.
#### 2. Visual studio를 열어 새로운 프로젝트를 생성합니다.
##### 3. 생성된 프로젝트에서 속성을 들어갑니다.
###### 4. 속성중 VC++디렉터리 에서 포함 디렉터리에 C:\opencv\build\include를 추가합니다
###### 5. 라이브러리 디렉터리에서 C:\opencv\build\x64\vc16\lib를 추가합니다.
###### 6. 링커 속성에서 추가종속성에 opencv_world480d.lib;opencv_world480.lib를 추가합니다.
###### 7. 프로젝트에서 새로운 main.cpp를 생성 후 원하는 소스를 입력하여 사용합니다. 
