# ✅ Vue 3 Todo App

Vue 3와 Composition API, Pinia를 사용하여 만든 **데이터 영구 저장 투두 리스트**입니다.  
사용자 경험(UX)을 고려하여 애니메이션, 스켈레톤 UI, 모달 등을 구현했습니다.

## 🚀 배포 링크 (Demo)

👉 **[앱 보러가기](https://mobee-vue-study.vercel.app/)**

---

## 🛠️ 기술 스택 (Tech Stack)

- **Core:** Vue 3, Composition API (Script Setup)
- **State Management:** Pinia
- **Styling:** SCSS (Sass)
- **Build Tool:** Vite
- **Deploy:** Vercel

---

## ✨ 주요 기능 (Key Features)

1.  **할 일 관리 (CRUD):** 할 일 추가, 수정(완료 체크), 삭제, 전체 삭제 기능
2.  **데이터 영속성 (Persistence):** `LocalStorage`를 활용하여 새로고침 해도 데이터 유지
3.  **고급 UX 패턴:**
    - `<TransitionGroup>`을 활용한 리스트 애니메이션
    - `Teleport`를 이용한 커스텀 모달(Modal) 창
    - 데이터 로딩 시 `Skeleton UI` 적용
    - `v-focus` 커스텀 디렉티브로 입력창 자동 포커싱
4.  **최적화:** `v-memo`, `Lazy Loading`을 통한 성능 최적화

---

## 📂 프로젝트 구조 (Structure)

```

src/
├── assets/          # CSS, Fonts, Images
├── components/      # 컴포넌트 (Header, Input, List, Modal...)
├── composables/     # 커스텀 훅 (useStorage)
├── directives/      # 커스텀 디렉티브 (v-focus)
├── stores/          # Pinia 스토어 (todo.js)
└── views/           # 페이지 (TodoApp.vue)

```

---

## 💿 실행 방법 (How to run)

```bash
# 1. 프로젝트 복제
git clone [https://github.com/모비아이디/레포지토리명.git](https://github.com/모비아이디/레포지토리명.git)

# 2. 패키지 설치
npm install

# 3. 개발 서버 실행
npm run dev

```

````

---

### ✅ 4주 차 4일 미션: 대문 꾸미기

1.  **작성:** 위 템플릿을 복사해 `README.md`에 붙여넣으세요.
2.  **수정:** `(여기에_모비님의_VERCEL_URL을_넣으세요)` 부분을 아까 만든 **실제 배포 주소**로 바꿔주세요.
3.  **푸시:** 깃허브에 올립니다.
    ```bash
    git add README.md
    git commit -m "docs: README 문서 작성"
    git push
    ```
4.  **확인:** 깃허브 저장소 페이지에 들어가서, 하단에 문서가 예쁘게 나오는지 확인하세요.

이제 누가 봐도 "아, 이 사람은 Vue 3와 Pinia를 제대로 쓸 줄 아는구나!"라고 알 수 있는 **완벽한 프로젝트**가 되었습니다.

작업을 마치고 **"학습 완료"**라고 말씀해 주세요.
이제 대망의 **마지막 날(졸업 및 회고)**만 남겨두고 있습니다! 🎓
````
