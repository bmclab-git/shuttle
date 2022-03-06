## shuttle

- Shuttle is a cross-platform network proxy tool based on Go.


#### 빌드 방법

- cd cmd
- build 1: go build -o shuttle.exe -tags release
- build 2: go build
- 빌드를 하면, cmd.exe 파일이 생긴다.
- cmd.exe 파일을 shuttle.exe 로 변경하여 사용한다.

#### 사전 준비 사항

- 실행파일 위치에 shuttle.yaml 파일이 있어야 한다.
- shuttle.yaml 파일은 proxy 환경설정 파일이다.
- 실행파일 위치에 GeoLite2-Country.mmdb 파일이 있어야 한다.
- GeoLite2-Country.mmdb 파일은 IP 주소에 따른 위치정보를 담고 있다.

#### 실행시 확인 사항

- shuttle 가 실행되면, 인터넷 연결이 proxy 설정에 따라 바뀌게 된다.
- shuttle.yaml 의 구성을 파악하여 설정한 후 사용한다.
- http://localhost:8082 로 접속하면 shuttle 의 대시보드에 접속된다.
- 대시보드에서 변경이나 설정을 하면 shuttle.yaml 파일이 수정된다.

