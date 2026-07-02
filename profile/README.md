# Openhash-Gopang

> **고팡은 기존 체제의 디지털 평행 세계다. 그 세계에는 주인이 없다.**
> **GDC는 193개국 시민 모두의 신용이다.**
> **그리고 그 세계의 헌법은 단 하나다 — DAWN: Democracy is All We Need.**

---

## 고팡이란 무엇인가

고팡(Gopang)은 비영리 글로벌 디지털 인프라다. 메시지 앱이 아니라, 현실 세계의 법원·중앙은행·행정기관의 AI 쌍둥이를 디지털 공간에 구축한 **평행 사회**다.

| 현실 기관 | 고팡 AI 쌍둥이 | 역할 |
|---------|--------------|------|
| 법원 | K-Law AI | 보완·보강, 접근성 현저히 향상 |
| 중앙은행 | GDC 통화 시스템 | 국적 화폐의 글로벌 보완재 |
| 국세청·세관 | K-Tax AI | 자동 보고, 투명성 확보 |
| 금융감독원 | K-Law AML 모듈 | 실시간 이상 거래 감지 |
| 상업 법원 | K-Law 분쟁 중재 | 당사자 합의 기반 자율 집행 |
| **민주주의** | **DAWN** | **참여 시민의 투표로 모든 것을 결정** |

고팡의 AI 쌍둥이 기관들은 현실 기관을 **대체하지 않는다.** 주권 국가의 고유 권한을 보완하고, 그 접근성을 현저히 향상시킨다.

---

## 핵심 기술

### PDV (Personal Data Vault)
모든 소통 데이터는 사용자 본인의 기기에 암호화되어 저장된다. 고팡, L1 중계 노드, 정부 기관 모두 사용자 동의 없이 접근할 수 없다. 데이터의 소유권은 온전히 사용자에게 있다.

### OpenHash
모든 소통이 발생하는 순간, 해시값이 물리적 계층 분산 네트워크에 즉시 등록된다. 한 번 등록된 해시는 변경이 수학적으로 불가능하다. 고팡의 모든 소통은 발생하는 순간 자동으로 법적 증거가 된다.

**PDV + OpenHash = Legal Hold 없이도 완결되는 자기완결 증거 구조.**

---

## K-Law 실증 성능

| 비교 쌍 | 일치도 | 표본 |
|--------|--------|------|
| K-Law ↔ 대법원 | **73%** | 300건 |
| 인간 원심(2심) ↔ 대법원 | 45% | 300건 |

대법원 선별 공개 판례(전체 소송의 0.01% 미만, 법리 최고 난이도) 기준. K-Law는 인간 원심 대비 **28%p** 높은 일치율을 달성했다. *(내부 측정값, 독립 제3자 검증 진행 중)*

---

## 이 Organization의 저장소 구성

| 저장소 | 설명 |
|--------|------|
| [gopang_v2](https://github.com/openhash-gopang/gopang_v2) | 고팡 메인 앱 — 메신저, PDV, AI 비서, K-Law 인터페이스 |
| [openhash-L1-ido1](https://github.com/openhash-gopang/openhash-L1-ido1) | L1 레이어 — IDO1 노드 |
| [openhash-L2-jeju-city](https://github.com/openhash-gopang/openhash-L2-jeju-city) | L2 레이어 — 제주시 |
| [openhash-L3-jeju](https://github.com/openhash-gopang/openhash-L3-jeju) | L3 레이어 — 제주도 |
| [openhash-L4-kr](https://github.com/openhash-gopang/openhash-L4-kr) | L4 레이어 — 대한민국 |
| [openhash-L5-global](https://github.com/openhash-gopang/openhash-L5-global) | L5 레이어 — 글로벌 |

---

## 공개 문서

> 아래 문서들은 갱신될 수 있습니다. 항상 최신본은 각 링크에서 확인하십시오.

| 문서 | 대상 | 링크 |
|------|------|------|
| GDC Whitepaper v1.5 | 투자자·파트너·일반 대중 | [보기](https://github.com/openhash-gopang/gopang_v2/blob/main/docs/GDC_Whitepaper_v1.5.md) |
| Gopang Address System v1.6 | 개발자·기술 검토자 | [보기](https://github.com/openhash-gopang/gopang_v2/blob/main/docs/Gopang_Address_System_v1.6.md) |
| Gopang PR LawFirm v1.3 | 법무법인·법률 전문가 | [보기](https://github.com/openhash-gopang/gopang_v2/blob/main/docs/Gopang_PR_LawFirm_v1.3.md) |
| Gopang Manual | 일반 사용자 | [보기](https://github.com/openhash-gopang/gopang_v2/blob/main/docs/GOPANG_MANUAL.md) |
| Release Notes v3.3 | 개발자 | [보기](https://github.com/openhash-gopang/gopang_v2/blob/main/docs/RELEASE_NOTES_v3.3.md) |

---

## 로드맵

| 항목 | 상태 |
|------|------|
| GAS v1.6 기술 명세 | 설계 완료, 구현 중 |
| PDV 발신자 서명 체계 | 개발 중 |
| OpenHash 앵커링 파이프라인 | 개발 중 |
| K-Law AI (한국 법률) | 내부 테스트 중 (대법원 일치율 73%) |
| GDC 통화 정책 스마트 컨트랙트 | 설계 완료, 개발 예정 |
| 법원 Verification API | 설계 완료, 개발 예정 |
| GDC 초기 세일 | 2026년 9월 예정 |
| 고팡 메신저 베타 | 2027년 1분기 예정 |
| 메인넷 출시 | 2027년 3분기 예정 |

---

## 참여

- **오류 발견:** Issue를 통해 신고
- **개선 제안:** Pull Request로 제출
- **법률·기술 검토 협력:** legal@hondi.net
- **개발 참여:** dev@hondi.net
- **일반 문의:** hello@hondi.net

---

> **본 Organization의 모든 문서는 공개 초안이다.**
> 실제 서비스 출시와 GDC 세일은 각국 규제 당국의 승인 및 법적 검토 완료 후 진행된다.
> 어떠한 내용도 투자 권유로 해석되어서는 안 된다.

*© 2026 AI City Inc. — DAWN 원칙에 따라 공개된다.*
*고팡은 특정 기업이나 국가가 소유하는 시스템이 아니다.*
