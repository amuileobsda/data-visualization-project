# data-visualization-project
## 목차 | Contents
1️⃣ [기획의도](#-기획의도--project-period) <br/>
2️⃣ [프로젝트 소개](#-프로젝트-소개--project-introduce) <br/>
3️⃣ [아키텍처](#-아키텍처--architecture) <br/>
4️⃣ [리눅스 LAMPN서버 구축 및 과정](#-리눅스-LAMPN서버-구축-및-과정) <br/>
5️⃣ [사이트 경로](#-사이트-경로) <br/>
6️⃣ [기술 스택](#-기술-스택--technology-stack) <br/>
7️⃣ [프로젝트 방향성](#-프로젝트-방향성) <br/>


## 기획의도
개발자가 1~3명인 중소기업이나 스타트업 같은 경우에는 자체 블로그가 아닌 `워드프레스`, `네이버 블로그` 등의 플랫폼을 통해 기술 블로그를 쓰는 경우가 종종 있습니다.

저는 이런 기업을 대상으로 기술 블로그를 만들어 구독료를 받고 운영할 수 있게 해주는 B2B 서비스를 만들 생각이었습니다.

하지만 이렇게 될 경우 관리나 유지보수를 제가 직접해야되기 때문에 기업입장에서 용이하지 못할 거 같은 생각이 들었습니다.

따라서 회사 내에서 직접 커스텀할수있게 서버구축부터 소스까지 전부 제공해 주자고 생각을 바꾸게 되었습니다.

생각 있으시면 연락해주세요 :)


## 프로젝트 소개
GA(Google Analytics)를 보면 사용자들이 웹사이트에 들어온 순간부터 모든 데이터를 활용하여 마케팅 도구로써 활용하고 있습니다. 

예를들어 클릭 수, 페이지 머무른 시간, 페이지 전환률, 자주 방문하는 페이지 … 등 이런 수많은 데이터를 활용하여 사이트의 활성화 방안을 찾는데 도움을 주는 툴입니다.

저는 이런 생각을 모방하여 블로그의 데이터를 활용해 모니터링 대시보드를 만들게 되었습니다.

html, tailwindcss, javascript, php, mysql를 이용해 블로그를 개발하였고 

해당 블로그에서 수집된 데이터로 node.js와 Chart.js 라이브러리를 이용해 모니터링 대시보드를 개발하였습니다.

블로그의 UI는 `Microsoft Edge`와 `Tistory` 사이트를 참고하였습니다.


## 아키텍처 | Architecture


## 리눅스 LAMPN서버 구축 및 과정
1) 서버에 Linux, Apache, Mysql, php, node.js 설치
2) certbot을 이용한 SSL 인증서 적용
3) 방화벽 설정
4) 포트추가
5) IP주소 필터링
6) 도메인 및 서브도메인 적용
7) 아파치 웹서버에 node서버추가


## 사이트 경로
|                                          |                               |  기술 스택                    |
| ---------------------------------------- | ----------------------------- | ----------------------------- |
| 블로그 사이트 경로                         | https://blog.ebosda.com        | php, javascript              |
| 블로그 모니터링 대시보드 경로               | http://blog.ebosda.com:4000    | express, ejs                 |
| 아이디                                    | test                           |                              |
| 패스워드                                  | test                           |                              |
| 리뉴얼한 블로그 사이트 경로                | https://next-ts.ebosda.com      | react, typescript, express   |


## 기술 스택 | Technology Stack
### FRONT-END
- JavaScript
- EJS
- TailwindCSS
- React.js
- Typescript

### BACK-END
- Node.js
- Express
- PHP
- Typescript

### DB
- MySQL
  
### ENGINEER
- Linux
- Apache
- CentOS
- PM2
- cron


## 프로젝트 방향성
<table>
  <tbody>
    <tr>
      <td>AWS를 사용안한 이유</td>
      <td>  </td>
    </tr>
    <tr>
      <td>B2C로 전향?</td>
      <td>  </td>
    </tr>
    <tr>
      <td>어떻게 수익모델을 만들것인가</td>
      <td> </td>
    </tr>
  </tbody>
</table>


## 
| 개발자                                      | 메일                       |
| ------------------------------------------- | -------------------------- |
| 최정길                                       | dev.ebosda000@gmail.com    |  
