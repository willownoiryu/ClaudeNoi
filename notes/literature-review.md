# 선행연구 목록

> 연구 주제: 클라우드 스토리지 용량 부족 알림의 **설득 전략**이 사용자의 정리 행동과 심리적 반발에 미치는 영향 — 보호 동기 이론을 중심으로
>
> 논문 목차(2장 이론적 배경, 3.4 측정 도구)에 맞춰 정리했어요. 목차는 [`thesis-outline.md`](thesis-outline.md) 8절에 있어요.
> BibTeX는 [`references/references.bib`](../references/references.bib)에 있어요. `[키]`로 본문에서 인용하면 돼요.
> ⭐ = 먼저 읽을 핵심 논문 (총 48편 중 11편)

## 먼저 읽을 순서 (추천)

| 순서 | 논문 | 왜 먼저 읽나 |
| --- | --- | --- |
| 1 | Rogers (1975) — 보호 동기 이론 | 연구 전체의 이론적 틀 |
| 2 | Witte (1992) — 확장 병렬 과정 모형 | 위협만 주면 왜 무시·반발하는지 설명 |
| 3 | Tannenbaum 외 (2015) — 위협 소구 메타분석 | 위협 + 대처 정보의 효과에 대한 가장 강한 근거 |
| 4 | Floyd 외 (2000) — 보호 동기 이론 메타분석 | 이론의 각 요소가 실제로 효과 있는지 |
| 5 | Khan 외 (2018) — 클라우드의 잊힌 파일 | 연구 배경(정리 필요성) |
| 6 | Brackenbury 외 (2021) — KondoCloud | "대처 정보(정리 추천)"의 선행 사례 |
| 7 | Dillard & Shen (2005) — 반발 측정 | 설득의 비용 측정 방법 |
| 8 | Oinas-Kukkonen & Harjumaa (2009) — 설득 시스템 설계 | 실험 조건(과업 단순화, 사회적 증거)의 근거 |

---

## 2.1 디지털 저장강박과 클라우드 정리 — "왜 안 지우는가, 정리를 어떻게 도울 수 있나"

연구 배경과 대상(정리하지 않는 사람)을 설명하는 문헌.

| | 논문 | 핵심 내용 | 이 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Sweeten, Sillence & Neave (2018). *Digital hoarding behaviours: Underlying motivations and potential negative consequences.* Computers in Human Behavior, 85, 54–60. `[sweeten2018digital]` | 45명 질적 연구. 과도한 축적, 삭제의 어려움, 불안 등 물리적 저장강박과 공통된 특성 | 저장강박의 정의와 동기 |
| | Neave, Briggs, McKellar & Sillence (2019). *Digital hoarding behaviours: Measurement and evaluation.* Computers in Human Behavior, 96, 72–77. `[neave2019digital]` | 디지털 저장강박 척도(DHQ) 개발 | → 3.4 측정 도구에도 정리 |
| | Vitale, Janzen & McGrenere (2018). *Hoarding and Minimalism: Tendencies in Digital Data Preservation.* CHI 2018. `[vitale2018hoarding]` | 23명 인터뷰. 저장강박형 ↔ 미니멀리스트형 스펙트럼 | 사용자 유형 구분 |
| | Sedera, Lokuge & Grover (2022). *Modern-day hoarding: A model for understanding and measuring digital hoarding.* Information & Management, 59(8). `[sedera2022modern]` | 애착 이론 기반 저장강박 모델. 저장 비용이 0에 가까워 축적 장벽이 사라짐 | 무료 용량이 축적을 부추긴다는 논리 |
| | Sillence, Dawson, Brown, McKellar & Neave (2023). *Digital hoarding and personal use digital data.* Human–Computer Interaction. `[sillence2023digital]` | 저장강박 점수와 개인 기기 사용 행동의 관계 | 저장강박 성향과 실제 행동의 연결 |
| | (저자 확인 필요) (2026). *Understanding digital hoarding: conceptual framework and future research based on a scoping review.* Humanities and Social Sciences Communications, 13, 1046. `[scoping2026digital]` | 최신 문헌 검토. **실증·개입 연구 부족**을 한계로 지적 | 연구 공백의 근거 |
| ⭐ | Khan, Hyun, Kanich & Ur (2018). *Forgotten But Not Gone: Identifying the Need for Longitudinal Data Management in Cloud Storage.* CHI 2018. `[khan2018forgotten]` | 클라우드 파일 중 50% 이상이 잊혔고, 참가자 48%가 절반 이상을 지우거나 암호화하고 싶어 함 | **정리 필요성이 실재한다는 핵심 근거** |
| ⭐ | Brackenbury, McNutt, Chard, Elmore & Ur (2021). *KondoCloud: Improving Information Management in Cloud Storage via Recommendations Based on File Similarity.* UIST 2021. `[brackenbury2021kondocloud]` | 유사 파일 기반 정리 추천. 추천을 받은 사용자가 관련 파일을 더 많이 정리함 | **"위협 + 대처 정보" 조건의 선행 사례**. 단, 설득·감정 반응은 다루지 않음 → 공백 |
| | Brackenbury, Harrison, Chard, Elmore & Ur (2021). *Files of a Feather Flock Together?* SIGIR 2021. `[brackenbury2021files]` | 사용자가 파일 유사성을 어떻게 인식하는지 측정 | 정리 추천 문구("비슷한 파일 23개") 설계 |
| | Ramokapane, Such & Rashid (2022). *What Users Want From Cloud Deletion and the Information They Need.* ACM TOPS, 26(1), 1–34. `[ramokapane2022cloud]` | 사용자는 실수로 지운 파일의 복구를 원함 | **"30일 안에 복구 가능" 문구의 근거** (정리의 반응 비용 낮추기) |
| | Boardman & Sasse (2004). *"Stuff goes into the computer and doesn't come out".* CHI 2004, 583–590. `[boardman2004stuff]` | 개인 정보 관리 전략 연구 | 고전적 배경 |
| | Bergman & Whittaker (2016). *The Science of Managing Our Digital Stuff.* MIT Press. `[bergman2016science]` | 개인 정보 관리 연구 종합 단행본 | 배경 서술 |
| | Oh (2024). *A comprehensive investigation of researchers' shared file management practices in cloud storage.* Human–Computer Interaction. `[oh2024shared]` | 규칙적으로 정리할수록 만족도 높음 | 정리의 이점 |

## 2.2 설득 이론 — "어떻게 설득하나" (연구의 핵심 틀)

| | 논문 | 핵심 내용 | 이 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Rogers (1975). *A protection motivation theory of fear appeals and attitude change.* The Journal of Psychology, 91(1), 93–114. `[rogers1975protection]` | 보호 동기 이론. 위협 평가(심각성·가능성)와 대처 평가(반응 효능·자기 효능·반응 비용)가 보호 행동을 결정 | **연구 전체의 이론적 틀.** 용량 부족 = 위협, 정리·결제 = 대처 행동 |
| ⭐ | Floyd, Prentice-Dunn & Rogers (2000). *A meta-analysis of research on protection motivation theory.* Journal of Applied Social Psychology, 30(2), 407–429. `[floyd2000meta]` | 65개 연구(약 3만 명) 메타분석. 위협 심각성·취약성, 반응 효능감, 자기 효능감이 높을수록, 반응 비용이 낮을수록 보호 행동 증가 | **가설 H1·H2의 근거.** 대처 정보가 반응 효능·자기 효능을 높이고 반응 비용을 낮춰야 하는 이유 |
| ⭐ | Witte (1992). *Putting the fear back into fear appeals: The extended parallel process model.* Communication Monographs, 59(4), 329–349. `[witte1992fear]` | 위협을 느낄 때 효능감이 높으면 문제를 해결하고(위험 통제), 낮으면 메시지를 거부·회피(공포 통제) | **"위협 제시" vs "위협 + 대처 정보" 조건 차이의 핵심 설명** (H2, H3-1) |
| ⭐ | Tannenbaum 외 (2015). *Appealing to fear: A meta-analysis of fear appeal effectiveness and theories.* Psychological Bulletin, 141(6), 1178–1204. `[tannenbaum2015fear]` | 위협 소구는 태도·의도·행동에 효과적이며, 효능 메시지가 함께 있을 때 효과가 큼 | **H2의 가장 강한 근거** |
| | Petty & Cacioppo (1986). *The elaboration likelihood model of persuasion.* Advances in Experimental Social Psychology, 19, 123–205. `[petty1986elaboration]` | 메시지를 깊이 따지는 경로(중심)와 단서로 판단하는 경로(주변) | 구체 정보("오래된 파일 23개, 4.2GB")가 설득력을 높이는 이유 |
| | Friestad & Wright (1994). *The Persuasion Knowledge Model: How People Cope with Persuasion Attempts.* Journal of Consumer Research, 21(1), 1–31. `[friestad1994persuasion]` | 설득 시도를 알아차리면 설득자에 대한 태도가 바뀜 | 설득이 서비스 태도에 영향을 주는 이유 (H3-3) |

## 2.3 디지털 설득과 넛지 — "디지털 서비스에서는 어떻게 설득하나"

| | 논문 | 핵심 내용 | 이 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Oinas-Kukkonen & Harjumaa (2009). *Persuasive Systems Design: Key Issues, Process Model, and System Features.* Communications of the AIS, 24, 28. `[oinaskukkonen2009persuasive]` | 설득 시스템 설계 모델. 28개 원칙을 과업 지원·대화 지원·신뢰성·사회적 지원 4범주로 분류 | **조건 3(과업 단순화)·조건 4(사회적 증거)의 근거** |
| | Kaptein, Markopoulos, de Ruyter & Aarts (2015). *Personalizing persuasive technologies: Explicit and implicit personalization using persuasion profiles.* International Journal of Human-Computer Studies, 77, 38–51. `[kaptein2015personalizing]` | 사람마다 잘 통하는 설득 전략이 다름 | **H4(저장강박 성향의 조절)의 근거** |
| | Thaler & Sunstein (2008). *Nudge.* Yale University Press. `[thaler2008nudge]` | 넛지 개념의 원전 | 넛지와 설득의 관계 서술 |
| | Weinmann, Schneider & vom Brocke (2016). *Digital Nudging.* Business & Information Systems Engineering, 58(6), 433–436. `[weinmann2016digital]` | UI 설계 요소로 행동을 이끄는 "디지털 넛지" 정의 | 개념 정의 |
| | Caraban, Karapanos, Gonçalves & Campos (2019). *23 Ways to Nudge.* CHI 2019. `[caraban2019nudge]` | HCI 넛지 23가지 기법, 6범주 | 설득 전략 후보 비교 |
| | Samuelson & Zeckhauser (1988). *Status quo bias in decision making.* Journal of Risk and Uncertainty, 1(1), 7–59. `[samuelson1988status]` | 현상 유지 편향 | 정리를 미루는 이유, 기본값(조건 3)의 효과 |
| | Kahneman, Knetsch & Thaler (1990). *Experimental tests of the endowment effect and the Coase theorem.* Journal of Political Economy, 98(6), 1325–1348. `[kahneman1990endowment]` | 보유 효과 | 가진 파일을 지우기 어려운 이유 (반응 비용) |

## 2.4 설득의 비용: 심리적 반발과 다크 패턴 — "설득이 지나치면"

### 심리적 반발

| | 논문 | 핵심 내용 | 이 연구에서의 쓰임 |
| --- | --- | --- | --- |
| ⭐ | Brehm (1966). *A Theory of Psychological Reactance.* Academic Press. `[brehm1966theory]` | 자유가 위협받으면 반발한다는 이론 | 설득의 비용에 대한 이론적 설명 |
| | Rosenberg & Siegel (2018). *A 50-year review of psychological reactance theory: Do not read this article.* Motivation Science, 4(4), 281–300. `[rosenberg2018reactance]` | 반발 이론 50년 연구 종합 | 반발 이론 서술 |
| ⭐ | Miller, Lane, Deatrick, Young & Potts (2007). *Psychological reactance and promotional health messages: The effects of controlling language, lexical concreteness, and the restoration of freedom.* Human Communication Research, 33(2), 219–240. `[miller2007reactance]` | 통제적 언어("반드시 ~하세요")는 반발을 높이고, 자유 회복 문구("선택은 당신에게")는 줄임. 구체적 언어는 주목도·평가를 높임 | **알림 문구 작성 기준** (H3-1) — 모든 조건에서 통제적 언어 배제 |
| ⭐ | Bruns & Perino (2023). *The role of autonomy and reactance for nudging.* Journal of Behavioral and Experimental Economics, 106, 102047. `[bruns2023autonomy]` | 기본값은 추천보다 자유를 더 위협한다고 느낌 | **H3-2(과업 단순화의 자유 위협)의 근거** |

### 다크 패턴과 서비스 평가

| | 논문 | 핵심 내용 | 이 연구에서의 쓰임 |
| --- | --- | --- | --- |
| | Gray, Kou, Battles, Hoggatt & Toombs (2018). *The Dark (Patterns) Side of UX Design.* CHI 2018. `[gray2018dark]` | 다크 패턴 유형 분류 | 설득과 조작의 경계 |
| | Mathur 외 (2019). *Dark Patterns at Scale.* Proceedings of the ACM on HCI, 3(CSCW). `[mathur2019dark]` | 쇼핑몰 1.1만 곳에서 다크 패턴 1,818건 | 다크 패턴 유형 참고 |
| | Luguri & Strahilevitz (2021). *Shining a Light on Dark Patterns.* Journal of Legal Analysis, 13(1), 43–109. `[luguri2021shining]` | 약한 다크 패턴은 가입률을 2배 이상, 강한 다크 패턴은 약 4배로 높임 | 압박이 단기 전환을 높인다는 근거 → 이 연구는 압박 대신 대처 정보로 설득 |
| | Voigt, Schlögl & Groth (2021). *Dark Patterns in Online Shopping: of Sneaky Tricks, Perceived Annoyance and Respective Brand Trust.* HCII 2021. `[voigt2021dark]` | 다크 패턴 버전에서 불쾌감이 높고, 불쾌감은 브랜드 신뢰와 관련 | **반발 → 서비스 태도(H3-3)의 근거** |
| | Gray, Chen, Chivukula & Qu (2021). *End User Accounts of Dark Patterns as Felt Manipulation.* Proceedings of the ACM on HCI, 5(CSCW2), 372. `[gray2021felt]` | 사용자가 "조종당한다"고 느끼는 경험 | 반발의 질적 이해 |
| | Bongard-Blanchy 외 (2021). *"I am Definitely Manipulated, Even When I am Aware of it. It's Ridiculous!"* DIS 2021. `[bongardblanchy2021manipulated]` | 다크 패턴을 알아채도 영향을 피하지 못함 | 행동과 반발을 따로 측정해야 하는 이유 |
| | 조보민·오선영·이지영·김은지·윤재영 (2023). 구독 해지 과정의 복잡성 정도에 따른 사용자 경험 연구: 다크패턴 디자인 인지 과정을 중심으로. 디자인학연구, 36(2), 247–265. `[jo2023subscription]` | 구독 해지 과정의 복잡성이 불쾌감과 재구독 의사에 영향 | 국내 구독 서비스 맥락의 불쾌감 근거 |
| | 정은선·윤재영 (2023). 사용자 속성에 따른 다크패턴(Dark Patterns) 인지 및 평가 연구. 한국HCI학회 논문지, 18(1), 37–49. `[jung2023darkpattern]` | 성별·세대·인터넷 능력에 따른 다크패턴 인지 차이 | 통제변수(연령 등) 선정 |
| | 이지혜·윤재영 (2023). 모바일 쇼핑 앱 다크 패턴 디자인이 사용자 경험에 미치는 영향: 조절 초점 성향별 감정 반응을 중심으로. 한국HCI학회 논문지. `[lee2023mobile]` | 조절 초점 성향에 따라 감정 반응이 다름 | 개인차 변수 후보 (권호·쪽수 확인 필요) |

## 3.4 측정 도구 — 척도 출처

| 변수 | 논문 | 척도 내용 | 비고 |
| --- | --- | --- | --- |
| **지각된 위협, 정리 효능감** | ⭐ Johnston & Warkentin (2010). *Fear Appeals and Information Security Behaviors: An Empirical Study.* MIS Quarterly, 34(3), 549–566. `[johnston2010fear]` | 정보보안 맥락의 보호 동기 이론 척도 (위협 심각성, 취약성, 반응 효능감, 자기 효능감). 부록에 문항 수록 | **디지털 서비스 맥락이라 스토리지 상황에 옮기기 가장 쉬움** |
| 지각된 위협, 정리 효능감, 공포 | Boss, Galletta, Lowry, Moody & Polak (2015). *What Do Systems Users Have to Fear? Using Fear Appeals to Engender Threats and Fear that Motivate Protective Security Behaviors.* MIS Quarterly, 39(4), 837–864. `[boss2015fear]` | 보호 동기 이론 전체 구성 개념(반응 비용 포함)과 위협 소구 조작을 함께 다룸 | **실험 조작 방법과 반응 비용 문항 참고** |
| 지각된 위협, 효능감 | Witte, Cameron, McKeon & Berkowitz (1996). *Predicting risk behaviors: Development and validation of a diagnostic scale.* Journal of Health Communication, 1(4), 317–341. `[witte1996predicting]` | 위험 행동 진단 척도(RBD). 확장 병렬 과정 모형 기반의 위협·효능 문항 | 건강 맥락이라 문항 수정 필요 |
| 심리적 반발 | Dillard & Shen (2005). *On the nature of reactance and its role in persuasive health communication.* Communication Monographs, 72(2), 144–168. `[dillard2005reactance]` | 분노 4문항 + 부정적 인지 | 반발 측정의 표준 |
| 심리적 반발 | Rains (2013). *The nature of psychological reactance revisited: A meta-analytic review.* Human Communication Research, 39(1), 47–73. `[rains2013reactance]` | 분노가 반발의 더 강한 지표 | 문항 구성 시 참고 |
| 지각된 침해감 | Edwards, Li & Lee (2002). *Forced exposure and psychological reactance: Antecedents and consequences of the perceived intrusiveness of pop-up ads.* Journal of Advertising, 31(3), 83–95. `[edwards2002forced]` | 팝업 광고의 침해감 척도 | 알림 형태가 팝업이면 추가 측정 |
| 디지털 저장강박 | ⭐ Neave, Briggs, McKellar & Sillence (2019). `[neave2019digital]` | DHQ 10문항 (축적, 삭제 어려움) | 조절변수 |
| 서비스 태도·신뢰 | McKnight, Choudhury & Kacmar (2002). *Developing and Validating Trust Measures for e-Commerce: An Integrative Typology.* Information Systems Research, 13(3), 334–359. `[mcknight2002trust]` | 온라인 서비스 신뢰(능력·호의·정직) | 서비스 태도 측정에 호의·정직 차원 활용 가능 |
| 결제 의향 | Mäntymäki, Islam & Benbasat (2020). *What drives subscribing to premium in freemium services?* Information Systems Journal, 30(2), 295–333. `[mantymaki2020premium]` | 유료 전환 요인과 의향 | 결제 의향 문항 참고 |
| 결제 의향 | Wagner, Benlian & Hess (2014). *Converting freemium customers from free to premium.* Electronic Markets, 24(4), 259–268. `[wagner2014converting]` | 지각된 프리미엄 적합성과 전환 | 결제 의향 문항 참고 |

## 참고: 채택하지 않은 발표안의 출발점 (2026-09-28 면담)

면담에서 발표한 "압박 수준 × 대안 출구" 방향은 채택되지 않았어요. 그때 근거로 쓴 세 논문은 위 목록에 포함되어 있어요.

| 발표 당시 원칙 | 논문 | 지금 목록에서의 위치 |
| --- | --- | --- |
| 압박 강도에 따라 반응이 달라지고, 강한 압박은 반발을 낳을 수 있다 | Luguri & Strahilevitz (2021) | 2.4 다크 패턴 |
| 위협과 함께 행동 가능한 대안을 주면 설득 효과가 높아진다 | Tannenbaum 외 (2015) | 2.2 설득 이론 (핵심 근거로 계속 사용) |
| 불쾌감은 서비스 이용 과정에서 누적된다 | 조보민 외 (2023) | 2.4 다크 패턴 |

## 아직 못 찾은 것 — 직접 찾아보기

학교 도서관을 통해 [RISS](https://www.riss.kr), [KCI](https://www.kci.go.kr), [DBpia](https://www.dbpia.co.kr)에서 아래 검색어로 찾아보세요.

**국내 연구 (가장 부족한 부분)**
- 보호 동기 이론, 공포 소구, 위협 소구, 효능 메시지
- 설득 메시지, 심리적 반발, 심리적 저항, 통제적 언어
- 디지털 저장강박, 디지털 호딩, 디지털 축적
- 다크 패턴, 다크 넛지, 디지털 넛지
- 클라우드 스토리지 이용 행동, 유료 전환 의도

**해외 연구**
- 보호 동기 이론 척도의 한국어 번역판 (국내 보안·건강 분야 연구에서 사용된 문항)
- 스토리지 용량 부족 알림, 업그레이드 프롬프트 관련 HCI 연구
- 사회적 증거(social proof) 메시지의 효과와 반발
- 사진 정리(photo curation) 행동 연구 — 스토리지 용량의 대부분이 사진이라 관련성 높음
