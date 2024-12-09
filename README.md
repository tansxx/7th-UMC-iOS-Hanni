# 7th-UMC-iOS-Hanni
---

## 📌 커밋 메시지 구조
1. **제목**: `<타입>: <제목>` 형식으로 작성
   - 제목은 50자 이내로 간결하게 작성
   - 변경 사항이 **무엇인지 명확히** 작성
   - **끝에 마침표 금지**
   - 예: `FEAT: 로그인 기능 추가`

2. **본문** (선택 사항): 변경 사항의 상세한 설명 작성
   - 여러 줄로 작성 가능하며, 각 줄은 **72자 이내**
   - 각 변경 사항을 `-` 기호로 구분
   - 예:
     ```
     - OAuth 2.0을 사용한 소셜 로그인 구현
     - 로그인 API 연동 완료
     ```

3. **꼬릿말** (선택 사항): 관련된 이슈 번호나 참고 정보를 작성
   - 예: `Close #7`

---

## 🛠 타입 가이드
커밋 메시지의 `타입`은 다음 중 하나를 선택합니다:

| 타입         | 설명                                                                 |
|--------------|----------------------------------------------------------------------|
| **FEAT**     | 새로운 기능 추가                                                   |
| **FIX**      | 버그 수정                                                          |
| **DOCS**     | 문서 수정 (README, 주석 등)                                        |
| **STYLE**    | 코드 포맷팅, 세미콜론 누락 등 코드 자체 변경이 없는 경우            |
| **REFACTOR** | 코드 리팩토링 (기능 변화 없음)                                      |
| **TEST**     | 테스트 코드 추가/수정                                              |
| **CHORE**    | 빌드 시스템 변경, 패키지 매니저 설정 등 자잘한 작업                 |

---

## ✏️ 커밋 메시지 템플릿
아래는 실제 커밋 메시지 작성 시 사용할 템플릿입니다:

```plaintext
# <타입>: <제목>
# 제목은 변경사항이 "무엇"인지 명확히 작성 (50자 이내, 끝에 마침표 금지)

# 본문
# 변경사항에 대한 구체적인 설명을 작성 (72자 이내, 여러 줄 가능)
# - 변경 이유 또는 해결한 문제 설명
# - 주요 변경 사항 나열

# 꼬릿말
# 관련된 이슈 번호 또는 참고 정보를 작성
# 예: Close #이슈번호
