---
layout: default
title: 스마트 디텍터 - 개인정보처리방침
---

# 개인정보처리방침

**스마트 디텍터** (Smart Detector, Android 패키지명: ai.fwth.smartdetector, 이하 "앱")는 **FWTH**(이하 "운영자")가 개발·운영하는 시험 감독 보조 앱입니다. 운영자는 「개인정보 보호법」 등 관련 법령을 지킵니다.

**앱 이름:** 스마트 디텍터 (Smart Detector)
**운영자:** FWTH
**연락처:** cjyh37@gmail.com
**최종 수정일:** 2026년 11월 16일
**시행일:** 2026년 11월 16일 (앱 0.11부터)

[English version below](#privacy-policy-english)

---

## 1. 요약

- 회원가입이 없고, 이름·이메일·전화번호를 묻지 않습니다.
- 앱이 수신한 무선 신호와 검사 기록은 **휴대폰 안에만 저장**되고 운영자에게 보내지 않습니다.
- 인터넷에 연결되어 있으면 앱 개선을 위한 **사용 통계**를 Google의 Firebase Analytics로 보냅니다.
- 광고 ID는 수집하지 않고, 광고를 넣지 않습니다.

---

## 2. 휴대폰 안에만 저장되는 정보

앱은 감독을 돕기 위해 주변 기기가 내보내는 Bluetooth(BLE)·Wi-Fi 신호를 수신합니다.

- **수신한 신호:** 기기가 광고하는 이름, 종류 단서, 신호 세기, 수신 시각, 주소에서 만든 구분값
- **검사 기록:** 시험실 이름, 시작 전·시작 후 신호 목록, 판단 메모, 수신하지 못한 시간

이 정보는 휴대폰의 앱 저장소에만 저장되며 운영자나 제3자에게 전송되지 않습니다. 기기 백업에도 포함하지 않습니다. 보고서를 다른 앱으로 공유하는 것은 사용자가 직접 할 때만 이루어집니다. 앱의 **본부** 메뉴에서 기록을 지울 수 있고, 앱을 삭제하면 모두 삭제됩니다.

주변 기기의 신호에는 다른 사람의 기기 이름이 들어 있을 수 있습니다. 앱은 이를 소유자와 연결하지 않으며, 소유자·좌석·부정행위 여부를 판정하지 않습니다.

---

## 3. 사용 통계 (Firebase Analytics)

앱 0.11부터, 인터넷에 연결되어 있을 때 다음 정보가 자동으로 Google LLC의 Firebase Analytics로 전송됩니다.

| 항목 | 내용 |
|------|------|
| 식별값 | 앱 설치마다 만들어지는 앱 인스턴스 ID, Firebase 설치 ID (이름·전화번호와 연결되지 않음) |
| 기기 정보 | 기기 모델, 운영체제 버전, 언어, 앱 버전 |
| 대략적 위치 | IP 주소로 추정한 국가·지역·도시 (GPS 위치는 수집하지 않음) |
| 사용 정보 | 앱 열기, 세션 시작, 사용 시간, 처음 실행·업데이트·삭제 같은 자동 이벤트 |

**보내지 않는 것:** 수신한 신호, 주변 기기 이름·주소, 검사 기록·보고서, 광고 ID, 설치 경로(캠페인) 정보. 광고 저장·광고 개인화 동의는 꺼 두었습니다.

- **목적:** 앱이 몇 대의 기기에서, 어떤 Android 버전에서 쓰이는지 파악해 호환성과 품질을 개선하기 위함
- **보유 기간:** Google Analytics의 데이터 보존 설정에 따라 보관 후 삭제됩니다.
- **거부 방법:** 앱 안에 끄는 설정은 아직 없습니다. 인터넷 연결 없이 사용하면 전송되지 않으며, 검사 기능은 인터넷 없이도 모두 사용할 수 있습니다. 앱을 삭제하면 이후 전송이 중단됩니다. 이미 전송된 통계의 삭제를 원하시면 아래 연락처로 요청해 주세요.

### 개인정보의 국외 이전

| 이전받는 자 | 이전 국가 | 이전 항목 | 이전 시기·방법 | 목적 | 보유 기간 |
|------|------|------|------|------|------|
| Google LLC (Firebase Analytics) | 미국 등 Google 데이터센터 소재국 | 3절의 사용 통계 항목 | 앱 사용 중 인터넷 연결 시 네트워크로 전송 | 앱 사용 통계 분석 | Google Analytics 보존 설정 기간 |

Google의 처리 방식은 [Google 개인정보처리방침](https://policies.google.com/privacy)과 [Firebase 개인정보 안내](https://firebase.google.com/support/privacy)를 참고해 주세요.

---

## 4. 앱 권한

| 권한 | 목적 | 필수 여부 |
|------|------|-----------|
| 주변 기기 (Bluetooth 검색·연결·광고) | 주변 BLE 신호 수신, 앱 자체 점검용 신호 송출 | 필수 |
| 정확한 위치 | Android가 Wi-Fi·Bluetooth 검색에 요구하는 권한. 앱은 GPS 위치를 읽거나 저장하지 않음 | 필수 |
| Wi-Fi 상태 | 주변 Wi-Fi 신호 수신 | 필수 |
| 알림 | 앱 밖에서 수신 중임을 알리고 멈출 수 있게 함 | 선택 |
| 포그라운드 서비스 | 다른 화면에 가도 수신을 이어 감 | 필수 |
| 인터넷 | 사용 통계 전송 | 자동 |

---

## 5. 제3자 제공

운영자는 사용자의 정보를 제3자에게 판매하거나 제공하지 않습니다. 3절의 사용 통계 처리를 위해 Google LLC(Firebase Analytics)를 이용합니다. 광고 SDK는 포함하지 않습니다.

---

## 6. 소개 사이트

소개 사이트(smartdetector.fwth.ai)는 Google Analytics로 페이지 방문과 APK 다운로드 버튼 클릭 수를 측정합니다.

---

## 7. 아동의 개인정보

앱은 시험 감독자를 위한 도구이며 만 14세 미만 아동을 대상으로 하지 않습니다. 아동의 개인정보를 의도적으로 수집하지 않습니다.

---

## 8. 개인정보처리방침의 변경

이 방침이 바뀌면 이 페이지와 앱 배포 안내(GitHub 릴리스)로 알립니다.

---

## 9. 문의

- **운영자:** FWTH
- **이메일:** cjyh37@gmail.com

---

<a id="privacy-policy-english"></a>

# Privacy Policy (English)

**Smart Detector** (Android package: ai.fwth.smartdetector, the "App") is an exam-proctoring aid developed and operated by **FWTH**.

**Contact:** cjyh37@gmail.com
**Last updated / Effective:** November 16, 2026 (from app version 0.11)

## Summary

- No account. The App never asks for your name, email or phone number.
- Received wireless signals and exam records are **stored only on your phone** and are never sent to us.
- When online, the App sends **usage statistics** to Google Firebase Analytics.
- No advertising ID is collected and the App shows no ads.

## Information stored only on your phone

The App receives Bluetooth (BLE) and Wi-Fi signals broadcast by nearby devices: advertised names, type hints, signal strength, time received and identifiers derived from addresses, together with exam records (room name, signal lists before and after the start, notes, and time the phone could not listen). These stay in the App's storage on the phone, are excluded from device backups, and are shared only if you choose to share a report. You can delete records from the App's **본부 (headquarters)** menu; uninstalling removes them all. The App does not link signals to their owners and does not determine whether cheating has occurred.

## Usage statistics (Firebase Analytics)

From version 0.11, when the phone is online, Google LLC's Firebase Analytics automatically receives: app instance ID and Firebase installation ID (not linked to your name or phone number); device model, OS version, language and app version; country, region and city estimated from the IP address (no GPS location); and automatic events such as app open, session start, engagement time, first open, update and removal.

**Not sent:** received signals, names or addresses of nearby devices, exam records or reports, advertising ID, or install campaign data. Ad storage and ad personalization consent are turned off.

Purpose: understanding how many devices and Android versions use the App, to improve compatibility and quality. Retention follows the Google Analytics data retention setting. There is no in-app switch yet; using the App offline sends nothing, and every exam feature works without internet access. Uninstalling stops further sending. To ask for deletion of statistics already sent, contact us. The data is processed by Google LLC, including in the United States. See the [Google Privacy Policy](https://policies.google.com/privacy) and [Firebase privacy information](https://firebase.google.com/support/privacy).

## Permissions

Nearby devices (Bluetooth scan, connect, advertise) to receive BLE signals and send the App's own self-test signal; precise location because Android requires it for Wi-Fi and Bluetooth scans (the App does not read or store GPS location); Wi-Fi state to receive Wi-Fi signals; notifications (optional) to show and stop listening away from the screen; foreground service to keep listening on other screens; internet for usage statistics.

## Website

The introduction site (smartdetector.fwth.ai) uses Google Analytics to count page visits and APK download button clicks.

## Children

The App is a tool for exam proctors and is not directed at children under 14. We do not knowingly collect children's information.

## Changes and contact

Changes are announced on this page and in the App's release notes on GitHub. Contact: FWTH, cjyh37@gmail.com.
