---
title: "거래소 API 연결하기"
description: "거래소 별 API 생성 방법을 확인하고 트레이덱스와 연동해 보세요."
---

---

## 공식 지원 거래소

현재 트레이덱스는 세 가지 글로벌 거래소를 지원하고 있어요.\
곧 업데이트를 통해 더 많은 거래소를 지원할 예정입니다.

<Frame>
  ![지원거래소](/images/지원거래소.png)
</Frame>

| 거래소 | 필요 정보 |
| --- | --- |
| 바이낸스 | API Key, API Secret |
| 바이비트 | API Key, API Secret |
| 비트겟 | API Key, API Secret, Passphrase |

<Tooltip tip="현재 트레이덱스는 세 가지 거래소만 지원하고 있습니다. 트레이덱스 채널을 통해 사용 거래소를 공유해주시면 빠르게 업데이트 후 공유드릴게요. " headline="Q. 다른 거래소를 사용 중인데 트레이덱스에 가입할 수 없나요?">Q. 다른 거래소를 사용 중인데 트레이덱스를 사용하고 싶어요</Tooltip>

---

## 바이낸스

바이낸스 계정 연동을 위해서는 **API Key**, **API Secret** 두 가지 정보가 필요해요.

1. 바이낸스 로그인 후 우측 상단 프로필 → **API Management** 클릭
2. **Create API** 버튼 클릭
3. API 유형: **System generated**
4. API 이름 입력 (예: Tradex)
5. 권한 설정: **Read Only** 선택
6. IP 제한: 비워두셔도 됩니다
7. 인증 완료 후 **API Key**와 **Secret Key** 복사 및 기록

> ⚠️ Secret Key는 최초 생성 시에만 확인 가능하니 반드시 저장해두세요.

---

## 바이비트

바이비트 계정 연동을 위해서는 **API Key**, **API Secret** 두 가지 정보가 필요해요.

1. 바이비트 우측 상단 프로필에서 **API** 클릭
2. API Management 페이지 우측 상단에 **Create New Key** 클릭
3. 상단의 **System-generated API Keys** 클릭
4. **API Transaction** 항목 선택
5. Name: Tradex 입력
6. API Key Permissions: **Read-Only**, **No IP restriction** 선택
7. 표의 모든 항목 선택
8. 제출 후 인증 완료 → **API Key**, **API Secret** 복사 및 기록

> ⚠️ API Secret은 최초 생성 시에만 확인 가능하니 반드시 저장해두세요.

---

## 비트겟

비트겟 계정 연동을 위해서는 **API Key**, **API Secret**, **Passphrase** 세 가지 정보가 필요해요.

1. 비트겟 우측 상단 프로필에서 **API Keys** 클릭
2. API Keys 탭에서 우측 상단 **Create API Key** 클릭
3. 상단의 **System-generated API Keys** 클릭
4. Note: `Tradex` 입력
5. Passphrase: 자주 사용하는 비밀번호 입력 후 반드시 기록
6. Permissions: **Read-Only**
7. Permission type: **Select all**
8. Bind IP Addresses: 비워두셔도 됩니다
9. 제출 후 인증 완료 → **API Key**, **API Secret**, **Passphrase** 복사 및 기록

---

## 자주 묻는 질문

**Q. 여러 거래소를 연결할 수 있나요?** 네 가능합니다. 단, Pro 요금제는 한 개의 계정만 지원하며 Premium 요금제부터 여러 계정을 동시에 연동하고 관리할 수 있어요.

**Q. 저는 다른 거래소를 쓰고 있어서 가입을 못해요.** 현재 트레이덱스 팀은 더 많은 거래소를 지원하기 위해 활발한 업데이트를 진행하고 있어요. 사용하시는 거래소를 접수해주시면 최대한 빠르게 업데이트하고 개별 연락드릴게요. 신청자가 많은 거래소 순서대로 지원할 예정이니 꼭 접수해주세요.