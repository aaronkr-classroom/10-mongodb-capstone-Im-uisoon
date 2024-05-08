[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15006467)
# Capstone 3: Adding MongoDB / MongoDB 추가하기

This capstone project involves adding MongoDB to our website. The website starter code we will use from now on is the midterm test project.<br>
이번 캡스톤 프로젝트에서는 MongoDB를 웹사이트에 추가합니다. 이제부터 사용할 웹사이트 스타터 코드는 중간고사 프로젝트입니다.

---

**Note:**

_Always remember_ to start MongoDB before running your application. There are two ways to do this:
항상 애플리케이션을 실행하기 전에 MongoDB를 시작하는 것을 잊지 마세요. 두 가지 방법이 있습니다.

1. Open a Git Bash terminal and run `mongod` to start the MongoDB server.<br>
   Git Bash 터미널을 열고 `mongod`를 실행하여 MongoDB 서버를 시작합니다.

```bash
$ mongod
```

2. Alternatively, you may also start the MongoDB server from MongoDB Compass.<br>
   또는 MongoDB Compass에서 MongoDB 서버를 시작할 수도 있습니다.

---

## Basic Requirements / 기본 요구사항

- [ ] `npm install mongodb mongoose`<br>
      Install the MongoDB and Mongoose packages.<br>
      MongoDB와 Mongoose 패키지를 설치하세요.
- [ ] Create new files for:
  - [ ] The Subscriber MODEL (`/models/Subscriber.js`). `2/2`<br>
        구독자 모델을 위한 새로운 파일을 생성하세요.
  - [ ] The subcriber VIEW (`/views/subscribers.ejs`). `2/2`<br>
        구독자 목록을 보여주는 뷰를 생성하세요.
  - [ ] The subscriber CONTROLLER (`/controllers/subscriberController.js`). `2/2`<br>
        구독자 컨트롤러를 위한 새로운 파일을 생성하세요.
- [ ] Add or update subscriber routes in `main.js`. `2/2`<br>
      `main.js`에 구독자 라우트를 추가하거나 업데이트하세요.

### Included files / 포함된 파일

```bash
|___/views
| |___/partials
| | |___header.ejs
| | |___footer.ejs
| | |___navigation.ejs
| | |___confetti.ejs
| |___layout.ejs
| |___index.ejs
| |___transportation.ejs
| |___contact.ejs
| |___thanks.ejs
| |___error.ejs
| |___`subscribers.ejs`             # <NEW> 구독자 목록을 보여주는 페이지

|___/public
| |___css
| | |___style.css
| | |___style.small.css
| | |___bootstrap.min.css
| | |___bootstrap.min.css.map
| | |___confetti.css
| |___img
| | |___dribbble_404.gif
| |___js
| | |___functions.js
| | |___bootstrap.bundle.min.js
| | |___bootstrap.bundle.min.js.map

|___/controllers
| |___homeController.js
| |___errorController.js
| |___`subscriberController.js`     # <NEW> Subscriber 모델을 처리하는 컨트롤러

|___/models                         # <NEW> 모델을 위한 폴더
| |___`Subscriber.js`               # <NEW> Subscriber 모델

|___`main.js`                       # <UPDATE> MongooDB 연결을 위해 수정 + 구독자 목록을 보여주는 라우트 추가
|___package.json
|___package-lock.json
```

### Assignment Points / 과제 점수

- **5-mongodb-capstone (NO TESTS) `(8/8)`** _(5월 12일까지)_
  - main.js `(2/2)`
  - /models/Subscriber.js `(2/2)`
  - /views/subscribers.ejs `(2/2)`
  - /controllers/subscriberController.js `(2/2)`