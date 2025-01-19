20여 년 관제노하우를 반영한 Playbook
이글루코퍼레이션의 20여 년 관제 노하우 기반으로 설계∙개발 된 Playbook
(민간/공공/금융 등 다양한 관제사이트에서 검증 된 관제 프로세스)

보안관제연구 전담 조직의 지속적인 Playbook⁠개발 및 지원⁠
(제품 구입 시 약 20여개 이상의 시나리오 기반의 플레이북 ⁠기본 제공)

SOC Optimization
국내 보안관제센터 업무에 최적화
Playbook을 통한 자동대응 뿐만 아니라 담당자에 의한
수동 대응 가능 (Automatic & Manually Response 기능 보유)

보안대응 뿐만 아니라 경보연동을 통한 시스템 장애 대응 가능

Automation
IGLOO Alliance 연동을 통한 자동차단
⁠IGLOO Alliance 협약 모델⁠ 운영 중

국내 최대 규모의 보안솔루션 연동 및 자동차단

F/W, IPS, NAC 등 자동차단을 위한 다양한 제품군 연동 (SECUI(방화벽), WINS(IPS) 등 국내 최다 사이트 구축 보안솔루션 연동 지속 확대)

Response Efficiency
AI 및 TI 연동을 통한 대응 효율 강화
국내 유일 지속 서비스 제공 중인 IGLOO CTI 연동을 통한 위협 인텔리전스 정보 제공 및 연동 ⁠(120개 이상의 고객사 연동 중)

머신러닝기반 보안관제시스템 분석 결과 연계를 통한 자동 대응 효율 강화 (SPiDER TM AI Edition 등 ML 기반 관제솔루션 연계)

Orchestration (오케스트레이션 여러 IT 프로세스를 조정하여 실행, 컴퓨터 시스템, 애플리케이션, 서비스 등을 관리하고 조율 하여 
복잡한 작업을 간소화하고 효율성을 높이는 데 사용)

SIEM, ML기반 보안 관제, 위협인텔리전스, 자산정보, 취약점 연동을 통해 Automation Response & Threat Intelligence 구현

# 시스템 구성도

## 1. 수집 (Collect) 보안장비로 대용량 Log 수집

SIEM(빅데이터 기반 보안관제시스템) : 네트워크 보안 시스템 (방화벽, IDS/IPS, DDoS, WAF(웹방화벽))
엔드포인트 보안시스템(서버보안, DB보안, 백신, PC보안)
정보자산 & 취약점 관리 & 위협 인텔리전스 : 내부 주요 서버(Windows, Unix, Linux 등)
IGLOO CTI (국내 위협 정보, 글로벌 위협정보, 최신 사이버위협정보)
```
취약점 분석 정보
자산정보
최신 유해 IP/URL
사이버 위협 동향
```

## 2. 탐지 (Detection) 

네트워크 보안 시스템, 엔드포인트 보안시스템 -> SIEM 빅데이터보안
```
실시간 저장 및 인덱싱
모든 Log 데이터 수집
대용량 Log 분석
실시간 상관분석
```
정보자산 & 취약점 관리 & 위협 인텔리전스
```
취약점 분석 정보
자산정보
최신 유해 IP/URL
사이버 위협 동향
```

## 3. 분석 Analysis

머신러닝 (AI) 기반 보안 관제 -> Response -> 위협 분석 -> ai 기반 종합 분석

## 4. 대응 Response

Automation : PlayBook 기반 사전 처리 자동화
Orchestration : 다양한 솔루션 및 데이터 연동
Event Response : 자동 차단
Case Management : 위협 중심 분석 및 대응 프로세스

<< SPiDER SOAR 기대 효과 >>

대응 시간 단축 및 신속한 의사 결정
대응 품질의 상향 평준화
프로세스 가시화
판단이 필요한 분석 업무에 전문업무 투입
수동 & 자동 실시간 관제
MTTR, MTTD, ROI 지표화
![image](https://github.com/user-attachments/assets/b2379932-8cca-4c5b-a364-ceb08ea0c4d9)
MTTR :  고장 난 시스템을 수리하고 정상 작동 상태로 복원하는 데 걸리는 평균 시간을 측정하는 데 사용되는 지표 
(Meam time to repair)
MTTD : 	– Mean Time To Detect (평균 장애 인지 시간)
– 장애 발생 시점 부터 장애 인지까지의 시간
ROI : 투자수익률(Return on Investment)을 의미하는 단어로, 투자자가 투자 활동을 살펴보고 다른 투자에 비해 특정 투자의 성과가 어떤지 파악하기 위해 사용하는 공식입니다. 간단히 말해, 투자수익률은 투자로 인해 얼마를 벌었거나 잃었는지를 보여줍니다.

장애 발생 ->인지->복구 완료의 시점으로 봤을 때 

발생 -> 인지 걸리는 시간 Mean time to detect MTTD 평균 장애 인지 시간
인지 -> 복구 걸리는 시간 Mean time to Repair MTTR 평균 복구 시간
복구완료 -> 다음 발생 걸리는 시간 Mean time to Failure 평균 가용 시간
발생 -> 다음 발생 걸리는 시간 Mean time to Between Failure 평균 장애 발생 기간
