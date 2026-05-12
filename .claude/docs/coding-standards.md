## 네이밍 컨벤션

### 파일명

- React 컴포넌트 : PascalCase (`UserProfile.tsx`)
- 유틸리티 : camelCase (`formatDate.ts`)
- 테스트 : `*.test.ts` 또는 `*.spec.ts`

### 변수/함수

- 변수 : camelCase (`userName`, `isLoading`)
- 상수 : UPPER_SNAKE_CASE (`API_BASE_URL`)
- 타입/인터페이스 : PascalCase (`UserProfile`, `ApiResponse`)
- Boolean: is/has/can 접두사 (`isValid`, `hasPermission`)

### 컴포넌트

- Props 타입 : `컴포넌트명Props` (`ButtonProps`)
- 이벤트 핸들러 : `handle접두사` (`handleClick`, `handleSubmit`)
