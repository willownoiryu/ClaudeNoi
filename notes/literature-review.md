# 선행연구 목록

> 연구 주제: 클라우드 스토리지에서 정리하지 않는 사용자를 대상으로, 불쾌감 없이 정리·결제를 이끄는 넛지 설계
>
> BibTeX는 [`references/references.bib`](../references/references.bib)에 있어요. `[키]`로 본문에서 인용하면 돼요.
> ⭐ = 먼저 읽을 핵심 논문

## 1. 디지털 저장강박 — "왜 안 지우는가"

연구 대상(정리하지 않는 사람)을 정의하고 측정하는 근거.

| | 논문 | 핵심 내용 | 내 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Sweeten, Sillence & Neave (2018). *Digital hoarding behaviours: Underlying motivations and potential negative consequences.* Computers in Human Behavior, 85, 54–60. `[sweeten2018digital]` | 45명 질적 연구. 과도한 축적, 삭제의 어려움, 불안 등 물리적 저장강박과 공통된 특성 확인 | 저장강박의 정의와 동기 |
| ⭐ | Neave, Briggs, McKellar & Sillence (2019). *Digital hoarding behaviours: Measurement and evaluation.* Computers in Human Behavior, 96, 72–77. `[neave2019digital]` | 디지털 저장강박 척도(DHQ) 개발. 10문항, '축적'과 '삭제 어려움' 두 요인 | **참가자 분류 척도로 사용 가능** |
| ⭐ | Vitale, Janzen & McGrenere (2018). *Hoarding and Minimalism: Tendencies in Digital Data Preservation.* CHI 2018. `[vitale2018hoarding]` | 23명 인터뷰. 저장강박형 ↔ 미니멀리스트형 스펙트럼 | 사용자 유형 구분의 근거 |
| | Sedera, Lokuge & Grover (2022). *Modern-day hoarding: A model for understanding and measuring digital hoarding.* Information & Management, 59(8). `[sedera2022modern]` | 애착 이론 기반 저장강박 모델. 저장 비용이 0에 가까워 축적 장벽이 사라졌다고 지적 | 무료 용량이 축적을 부추긴다는 논리 |
| | Sillence, Dawson, Brown, McKellar & Neave (2023). *Digital hoarding and personal use digital data.* Human–Computer Interaction. `[sillence2023digital]` | 저장강박 점수와 개인 기기 사용 행동의 관계 | 저장강박 성향과 실제 행동의 연결 |
| | (저자 확인 필요) (2026). *Understanding digital hoarding: conceptual framework and future research based on a scoping review.* Humanities and Social Sciences Communications, 13, 1046. `[scoping2026digital]` | 최신 scoping review. 동기(정서·도구·통제·정체성)별 저장강박 유형. **실증 연구 부족**을 한계로 지적 | 연구 공백의 근거 |

## 2. 개인 정보 관리(PIM)와 클라우드 정리 — "정리를 어떻게 도울 수 있나"

| | 논문 | 핵심 내용 | 내 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Khan, Hyun, Kanich & Ur (2018). *Forgotten But Not Gone: Identifying the Need for Longitudinal Data Management in Cloud Storage.* CHI 2018. `[khan2018forgotten]` | Dropbox·Google Drive 파일 중 50% 이상이 잊혔고, 참가자 48%가 파일 절반 이상을 지우거나 암호화하고 싶어 함 | **정리 필요성이 실재한다는 핵심 근거** |
| ⭐ | Brackenbury, McNutt, Chard, Elmore & Ur (2021). *KondoCloud: Improving Information Management in Cloud Storage via Recommendations Based on File Similarity.* UIST 2021. `[brackenbury2021kondocloud]` | 유사 파일 기반 정리 추천 인터페이스. 약 절반이 추천을 상당 부분 수락 | **"추천형 넛지"의 선행 사례**. 단, 감정 반응은 측정 안 함 → 공백 |
| | Brackenbury, Harrison, Chard, Elmore & Ur (2021). *Files of a Feather Flock Together?* SIGIR 2021. `[brackenbury2021files]` | 사용자가 파일 유사성을 어떻게 인식하는지 측정 | 정리 추천 로직의 근거 |
| | Ramokapane, Such & Rashid (2022). *What Users Want From Cloud Deletion and the Information They Need.* ACM TOPS, 26(1), 1–34. `[ramokapane2022cloud]` | 참여형 연구. 사용자는 삭제 방식에 대해 다양한 요구가 있고, 실수로 지운 파일의 복구를 원함 | 삭제 불안 해소 설계(복구 가능성 안내) |
| | Boardman & Sasse (2004). *"Stuff goes into the computer and doesn't come out".* CHI 2004, 583–590. `[boardman2004stuff]` | 파일·이메일·북마크에 걸친 개인 정보 관리 전략 연구 | PIM 분야의 고전적 배경 |
| | Bergman & Whittaker (2016). *The Science of Managing Our Digital Stuff.* MIT Press. `[bergman2016science]` | PIM 연구를 종합한 단행본 | 이론적 배경 장 서술 |
| | Oh (2024). *A comprehensive investigation of researchers' shared file management practices in cloud storage.* Human–Computer Interaction. `[oh2024shared]` | 534명 설문. 규칙적으로 정리할수록 만족도 높음 | 정기 정리의 효과 근거 |

## 3. 넛지와 디지털 넛지 — "어떻게 행동을 이끄나"

| | 논문 | 핵심 내용 | 내 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Thaler & Sunstein (2008). *Nudge.* Yale University Press. `[thaler2008nudge]` | 넛지 개념의 원전 | 이론적 틀 |
| ⭐ | Weinmann, Schneider & vom Brocke (2016). *Digital Nudging.* Business & Information Systems Engineering, 58(6), 433–436. `[weinmann2016digital]` | UI 설계 요소로 행동을 이끄는 "디지털 넛지" 정의 | 핵심 개념 정의 |
| ⭐ | Caraban, Karapanos, Gonçalves & Campos (2019). *23 Ways to Nudge.* CHI 2019. `[caraban2019nudge]` | HCI 넛지 23가지 기법을 6범주로 분류, 15개 인지 편향과 연결 | **실험 조건(넛지 유형) 설계의 근거** |
| | Samuelson & Zeckhauser (1988). *Status quo bias in decision making.* Journal of Risk and Uncertainty, 1(1), 7–59. `[samuelson1988status]` | 현상 유지 편향 | 정리를 미루는 이유 |
| | Kahneman, Knetsch & Thaler (1990). *Experimental tests of the endowment effect and the Coase theorem.* Journal of Political Economy, 98(6), 1325–1348. `[kahneman1990endowment]` | 보유 효과 | 가진 파일을 지우기 어려운 이유 |

## 4. 불쾌감: 심리적 반발 — "왜 넛지가 불쾌한가"

| | 논문 | 핵심 내용 | 내 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Brehm (1966). *A Theory of Psychological Reactance.* Academic Press. `[brehm1966theory]` | 자유가 위협받으면 반발한다는 이론 | **불쾌감의 이론적 설명** |
| ⭐ | Dillard & Shen (2005). *On the nature of reactance and its role in persuasive health communication.* Communication Monographs, 72(2), 144–168. `[dillard2005reactance]` | 반발을 '분노 + 부정적 인지'로 측정하는 방법 제시 | **불쾌감 측정 척도** |
| | Edwards, Li & Lee (2002). *Forced exposure and psychological reactance: Antecedents and consequences of the perceived intrusiveness of pop-up ads.* Journal of Advertising, 31(3), 83–95. `[edwards2002forced]` | 팝업 광고의 지각된 침해감 척도 | 알림·팝업형 넛지의 침해감 측정 |
| ⭐ | Bruns & Perino (2023). *The role of autonomy and reactance for nudging.* Journal of Behavioral and Experimental Economics, 106, 102047. `[bruns2023autonomy]` | 기본값은 추천보다 자유를 더 위협한다고 느끼지만 더 짜증 나지는 않음. 의무는 둘 다 높음 | **넛지 유형별 반발 차이의 선행 근거** |

## 5. 다크 패턴 — "넛지의 윤리적 경계"

| | 논문 | 핵심 내용 | 내 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Gray, Kou, Battles, Hoggatt & Toombs (2018). *The Dark (Patterns) Side of UX Design.* CHI 2018. `[gray2018dark]` | 다크 패턴 유형 분류 | 결제 유도 넛지가 넘지 말아야 할 선 |
| | Mathur et al. (2019). *Dark Patterns at Scale.* Proceedings of the ACM on HCI, 3(CSCW). `[mathur2019dark]` | 쇼핑몰 1.1만 곳에서 다크 패턴 1,818건 발견, 15유형 | 다크 패턴 유형 참고 |

## 6. 프리미엄(Freemium) 결제 전환 — "왜 결제하나"

| | 논문 | 핵심 내용 | 내 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Mäntymäki, Islam & Benbasat (2020). *What drives subscribing to premium in freemium services?* Information Systems Journal, 30(2), 295–333. `[mantymaki2020premium]` | 정서·기능·사회·인식·경제적 가치가 유료 전환과 유지에 미치는 영향 | 결제 의향 요인 |
| | Wagner, Benlian & Hess (2014). *Converting freemium customers from free to premium.* Electronic Markets, 24(4), 259–268. `[wagner2014converting]` | '지각된 프리미엄 적합성'이 전환에 중요 | 결제 의향 측정 참고 |

## 아직 못 찾은 것 — 직접 찾아보기

**국내 연구**는 웹 검색으로는 이 주제와 직접 맞는 KCI 논문을 찾지 못했어요. 학교 도서관을 통해
[RISS](https://www.riss.kr), [KCI](https://www.kci.go.kr), [DBpia](https://www.dbpia.co.kr)에서 아래 검색어로 찾아보세요.

- 디지털 저장강박, 디지털 호딩, 디지털 축적
- 디지털 넛지, 넛지 수용성, 다크 넛지, 다크 패턴
- 심리적 반발, 심리적 저항, 지각된 침해성
- 클라우드 스토리지 이용 행동, 프리미엄 전환, 유료 전환 의도

**추가로 찾아볼 해외 주제**
- 스토리지 용량 부족 알림, 업그레이드 프롬프트 관련 HCI 연구
- 손실 프레이밍 vs 이득 프레이밍 메시지 효과
- 사진 정리(photo curation) 행동 연구 — 스토리지 용량의 대부분이 사진이라 관련성 높음
