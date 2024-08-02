# Inilink Gateway Admin Frontend

## 주요 기능

### 핸들러 관리
- **핸들러 소스 코드 업로드, 조회, 수정, 삭제 기능**
- **핸들러 목록 및 상세 정보 조회 기능**

### 라우팅 설정 관리
- **라우팅 설정 추가, 조회, 수정, 삭제 기능**
- **핸들러 조합 기능 (Drag & Drop 방식)**

### 배포 및 모니터링
- **배포 관리 기능**
- **실시간 상태 및 성능 모니터링 기능**
- **알림 설정 기능**

## 기술 스택
- **Vue.js**: UI 프레임워크
- **Vuex**: 상태 관리
- **Vue Router**: 라우팅 관리
- **Axios**: HTTP 요청 라이브러리


## 프로젝트 설정

1. **프로젝트 클론**
    ```bash
    git clone https://github.com/yourusername/inilinkgateway-admin-frontend.git
    cd inilinkgateway-admin-frontend
    ```

2. **종속성 설치**
    ```bash
    npm install
    ```

3. **개발 서버 실행**
    ```bash
    npm run serve
    ```

## 프로젝트 구조 설명

- **public/**: 공개 정적 파일
- **src/**: 소스 코드 디렉토리
  - **assets/**: 이미지 및 기타 자산
  - **components/**: Vue 컴포넌트
    - **Handler/**: 핸들러 관리 관련 컴포넌트
      - **HandlerList.vue**: 핸들러 목록 컴포넌트
      - **HandlerUpload.vue**: 핸들러 업로드 컴포넌트
    - **Route/**: 라우팅 설정 관리 컴포넌트
      - **RouteList.vue**: 라우팅 설정 목록 컴포넌트
      - **RouteConfig.vue**: 라우팅 설정 컴포넌트
  - **router/**: Vue Router 설정
    - **index.js**: 라우터 설정 파일
  - **store/**: Vuex 상태 관리
    - **index.js**: Vuex 스토어 설정 파일
    - **handler.js**: 핸들러 상태 관리 모듈
    - **route.js**: 라우팅 상태 관리 모듈
  - **views/**: 페이지 뷰 컴포넌트
    - **Dashboard.vue**: 대시보드 뷰
    - **Handlers.vue**: 핸들러 관리 뷰
    - **Routes.vue**: 라우팅 설정 관리 뷰
  - **App.vue**: 최상위 Vue 컴포넌트
  - **main.js**: 진입점 파일
- **tests/**: 테스트 파일
- **package.json**: 프로젝트 메타데이터 및 종속성
- **vue.config.js**: Vue CLI 설정 파일

## 라이선스
[MIT](LICENSE)


