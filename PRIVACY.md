# 개인정보처리방침 / Privacy Policy

**앱 이름**: 일본어 단어 학습 (JLPT단어)
**개발자**: Sejun
**연락처**: seguneman@gmail.com
**최종 수정일**: 2026-05-27
**버전**: 0.1.0-beta

---

## 한국어

### 1. 개요
본 앱은 학습자가 일본어 단어를 오프라인으로 학습할 수 있도록 만든 모바일 앱입니다.
사용자의 개인정보를 **수집하지 않으며**, 외부 서버로 데이터를 전송하지 않습니다.
다만, 무료 운영을 위해 광고(AdMob) SDK 를 사용하며, 광고 SDK 자체가 일부 정보를 수집할 수 있습니다.

### 2. 수집하지 않는 정보
다음 정보를 본 앱은 **직접 수집하지도, 외부 서버로 전송하지도 않습니다**:
- 사용자 이름, 이메일, 전화번호, 주소
- 위치 정보
- 연락처, 사진, 파일, SMS
- 마이크, 카메라
- 회원가입 / 로그인 정보 (앱에 로그인 기능 자체가 없음)

### 3. 기기에 저장되는 정보 (앱 내부)
다음 정보는 사용자의 기기 안에서만 저장되며, 외부로 전송되지 않습니다:
- 학습 진도 (어떤 단어를 알아요/모름으로 표시했는지)
- 즐겨찾기 ★ 단어 목록
- SRS(간격 반복) 학습 일정
- 마지막 본 단어 위치, 카테고리 선택, 다크 모드 설정 등
- 연속 학습 일수 / 일일 학습 카운트

위 정보는 모두 안드로이드의 `localStorage` 에 저장되며, 앱을 삭제하면 함께 사라집니다.
사용자는 안드로이드 [설정 → 앱 → 일본어 단어 학습 → 저장공간 → 데이터 삭제] 로 언제든 직접 삭제할 수 있습니다.

### 4. 광고 (Google AdMob)
앱 운영비를 위해 Google AdMob 배너 광고를 표시합니다.
AdMob 은 광고 맞춤화를 위해 다음 정보를 수집할 수 있습니다:
- 광고 ID (Advertising ID) — 안드로이드 시스템이 제공하는 익명 식별자
- 기기 정보 (모델명, OS 버전, 언어, 국가)
- 광고 노출 / 클릭 통계

자세한 내용은 Google 의 개인정보처리방침을 참고하세요:
- https://policies.google.com/privacy
- https://support.google.com/admob/answer/6128543 (광고 ID 관리)

사용자는 안드로이드 [설정 → Google → 광고] 에서 광고 ID 를 재설정하거나 광고 맞춤화를 끌 수 있습니다.

### 5. 권한
앱이 안드로이드 시스템에 요청하는 권한은 다음과 같습니다:
- **INTERNET**: 광고 SDK 통신 (학습 콘텐츠 자체는 오프라인 동작)
- **ACCESS_NETWORK_STATE**: 광고 로딩 전 네트워크 상태 확인

위치, 카메라, 연락처, 마이크, 저장소 등 **민감 권한은 일절 요청하지 않습니다**.

### 6. 어린이 보호 (COPPA)
본 앱은 모든 연령대를 대상으로 합니다.
만 13세 미만 사용자의 개인정보는 별도로 수집하지 않습니다.
앱 자체가 사용자 식별 정보를 수집하지 않으므로, COPPA 관련 규제 대상에 해당하지 않습니다.

### 7. 데이터 보안
앱 내부 학습 데이터(단어, 예문 등)는 AES-256-GCM 으로 암호화되어 APK 에 번들됩니다.
사용자 학습 진도는 안드로이드 시스템의 보안 영역에 저장됩니다.

### 8. 정책 변경
본 정책이 변경되는 경우 앱 업데이트 시 변경 사항을 안내드립니다.

### 9. 문의
본 정책에 대한 문의는 다음으로 연락 주십시오:
- 이메일: seguneman@gmail.com

---

## English

### 1. Overview
This app is an offline Japanese vocabulary learning app for Korean learners.
We do **not collect any personal information** and do not transmit any data to external servers.
However, we use Google AdMob for advertising, which may collect limited information itself.

### 2. Information We Do NOT Collect
- Name, email, phone number, address
- Location data
- Contacts, photos, files, SMS
- Microphone, camera
- Login credentials (the app has no login feature)

### 3. Information Stored Locally on Device
The following data is stored only in the user's device `localStorage` and is never sent externally:
- Learning progress (known/unknown markings)
- Favorite (★) word list
- SRS (spaced repetition) schedule
- Last viewed position, category selection, theme preference
- Daily learning count, streak days

Users can delete this data anytime via Android [Settings → Apps → 일본어 단어 학습 → Storage → Clear Data].

### 4. Advertising (Google AdMob)
We display Google AdMob banner ads to fund free operation.
AdMob may collect:
- Advertising ID (anonymous identifier provided by Android)
- Device information (model, OS, language, country)
- Ad impression/click stats

See Google's privacy policy for details:
- https://policies.google.com/privacy
- https://support.google.com/admob/answer/6128543

Users can reset their Advertising ID or opt out of personalized ads via Android [Settings → Google → Ads].

### 5. Permissions
- **INTERNET**: For ad SDK communication (learning content itself works offline)
- **ACCESS_NETWORK_STATE**: To check network state before loading ads

We do **not request** sensitive permissions (location, camera, contacts, microphone, storage).

### 6. Children's Privacy (COPPA)
The app is suitable for all ages and does not knowingly collect data from users under 13.
Since we collect no identifying information, the app is not subject to COPPA regulations.

### 7. Data Security
In-app learning data (vocabulary, examples) is encrypted with AES-256-GCM and bundled inside the APK.
User progress is stored in Android's secure local storage area.

### 8. Policy Changes
Any changes to this policy will be announced via app updates.

### 9. Contact
For questions about this policy, please contact:
- Email: seguneman@gmail.com
