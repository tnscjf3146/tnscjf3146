# assets

README에서 쓰는 **프로젝트 이미지·GIF**를 넣는 폴더.

## 구조

```
assets/
├── honja-soonuri/   혼자소누리 (관통)
├── saekomi/         새코미 (공통)
└── g-shared/        G-SHARED (특화)
```

## 사용법

```markdown
![혼자소누리 메인](assets/honja-soonuri/main.png)
```

크기 조절은 HTML 태그로. 마크다운 문법으로는 안 된다.

```html
<img src="assets/honja-soonuri/demo.gif" width="600">
```

나란히 배치하려면 표를 쓴다.

```markdown
| 메인 | 상세 |
|---|---|
| <img src="assets/saekomi/main.png" width="400"> | <img src="assets/saekomi/detail.png" width="400"> |
```

## 아이콘은 여기 넣지 말 것

기술 스택 아이콘은 파일 대신 **shields.io 배지**를 쓴다. 관리할 파일이 없고 해상도도 안 깨진다.

```markdown
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
```

로고 이름은 https://simpleicons.org 에서 검색한다.
색상은 `-` 뒤 여섯 자리 hex를 바꾸면 된다.

## 주의

- GIF는 **10MB 이하**. 넘으면 GitHub에서 안 뜨거나 매우 느려진다
- 파일명은 영문·숫자·하이픈으로. 한글·공백은 경로가 깨질 수 있다
- 이 저장소는 **공개**다. 개인정보나 API 키가 찍힌 화면은 올리지 말 것
