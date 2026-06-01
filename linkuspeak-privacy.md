# 린쿠스피쿠 개인정보처리방침 / Privacy Policy

**앱 이름**: 린쿠스피쿠 (LinkuSpeak, `com.linkuspeak.app`)
**개인정보 관련 문의**: seguneman@gmail.com
**최종 수정일**: 2026-06-01

---

## 1. 개요

린쿠스피쿠(이하 "본 앱")는 한국인 학습자를 위한 일본어 회화 발음 연습 앱입니다.
**회원가입·로그인이 필요하지 않으며, 이메일·이름·전화번호 등 개인을 식별하는 정보를 수집하지 않습니다.**
학습 데이터는 사용자 기기에 보관되며, 앱은 무료로 제공되고 **광고가 표시**됩니다.

## 2. 수집·처리하는 정보

| 항목 | 목적 | 처리 방식 | 보관 |
|---|---|---|---|
| **마이크 음성** | 발음 채점(음성 → 텍스트 변환) | 아래 3항 참조 | **저장하지 않음**(채점 직후 폐기) |
| **학습 진도**(레슨 완료/점수/즐겨찾기/연속일) | 진행 상황 표시 | 기기 `localStorage` | 기기 내부 저장(서버 전송 없음) |
| **앱 사용 활동·기기 식별자** | 사용 통계·기능 개선 | Google Firebase Analytics(GA4) | 아래 4항 |
| **광고 식별자(기기 광고 ID)·앱 활동** | 광고 게재 | Google AdMob | 아래 4항 |

이름·이메일·전화번호·위치·연락처는 수집하지 않으며, **계정·비밀번호가 없습니다.**

## 3. 마이크 음성의 처리 (중요)

발음 채점을 위해, 사용자가 마이크 버튼을 누르고 말한 음성을 **음성 인식(STT)** 으로 처리합니다.

- 기본적으로 **기기에 내장된 음성 인식 서비스**(대개 Google 음성 인식)를 사용합니다.
- 일부 환경에서는 브라우저 기반 음성 인식(WebSpeech)을 폴백으로 사용하며, 이 경우 **음성이 Google 음성 인식 서버로 전송·처리될 수 있습니다.**
- 변환된 텍스트는 화면상의 채점에만 사용되며, **음성·텍스트 모두 본 앱이나 개발자 서버에 저장하지 않고 채점 직후 폐기**합니다.
- 음성 인식 서비스 제공자(Google)의 처리에는 해당 사업자의 개인정보처리방침이 적용됩니다.

마이크 권한은 발음 채점 기능에만 사용됩니다.

## 4. 제3자 서비스

각 사의 개인정보처리방침이 적용됩니다.

- **Google 음성 인식**: 위 3항에 따라 음성이 전송·처리될 수 있음.
- **Google Firebase Analytics**: 앱 사용 이벤트(화면 진입, 레슨 시작/완료 등)와 기기·앱 식별자(앱 인스턴스 ID 등)를 수집하여 익명·통계 형태로 사용 현황을 분석합니다. 개인을 직접 식별하지 않습니다.
- **Google AdMob**: 무료 이용자에게 광고를 게재하며, 광고 식별자(기기 광고 ID)와 앱 활동 정보를 광고 목적에 사용할 수 있습니다.

## 5. 권한

| 권한 | 사용 목적 |
|---|---|
| 마이크(RECORD_AUDIO) | 발음 채점을 위한 음성 입력 |
| 인터넷(INTERNET) | 음성 인식·분석·광고 통신 |
| 알림(POST_NOTIFICATIONS) | 학습 리마인더(사용자가 켤 때만) |

## 6. 아동의 개인정보

본 앱은 만 13세 이상을 대상으로 하며, 아동을 주 대상으로 하지 않습니다.

## 7. 데이터 보관 및 삭제

- **음성 데이터**: 보관하지 않음(채점 직후 폐기).
- **학습 진도**: 기기에 저장되며, **앱 삭제 시 함께 삭제**됩니다. 앱 내 "진도 초기화"로도 삭제할 수 있습니다.
- **계정 없음**: 본 앱은 별도 계정을 만들지 않으므로 서버에 저장된 개인 계정 데이터가 없습니다.
- 광고 식별자는 기기 설정에서 재설정·삭제할 수 있습니다(설정 → Google → 광고).

## 8. 방침 변경

본 방침이 변경되는 경우 앱 업데이트 및 본 페이지를 통해 고지합니다.

## 9. 문의

개인정보 관련 문의: **seguneman@gmail.com**

---

## English (Summary)

**LinkuSpeak** (`com.linkuspeak.app`) is a free, ad-supported Japanese speaking-practice app for Korean learners. **No sign-up or login is required, and we do not collect personally identifying information** (no email, name, or phone number; no account or password).

- **Microphone audio**: processed by on-device speech recognition (usually Google) for pronunciation scoring; **not stored** — discarded immediately after scoring. In some environments a browser-based fallback may send audio to Google's speech servers.
- **Learning progress**: stored locally on the device (`localStorage`); deleted when the app is uninstalled.
- **Usage analytics**: Google Firebase Analytics collects app events and device/app identifiers in aggregate (no direct personal identification).
- **Advertising**: Google AdMob may use the device advertising ID and app activity to serve ads to free users.

Permissions: Microphone (scoring), Internet (speech/analytics/ads), Notifications (optional reminders). Intended for users 13+.

Contact: **seguneman@gmail.com** · Last updated: 2026-06-01
