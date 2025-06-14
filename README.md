# information_security
보안아키텍쳐의 설계 교육 학습자료

# 1일차(2024/12/16)
- CIS 벤치마크, SIP
- ISMS-P 인증심사원
- Wazuh
<details>
  
### 1. 정보 보안의 이해
##### 보안의 3대 요소
- 무결성, 가용성, 기밀성
##### 보안 전문가의 자격 요건
- 운영체제, 네트워크, 프로그래밍, 서버

### 2. 정보보안 아키텍처
##### X.805 아키텍처
- 주요목표: 인프라/서비스/애플리케이션 보안
- 주요요소
  - 보안차원: 접근제어, 인증, 무결성, 기밀성, 통신 무결성, 통신 보안, 가용성, 프라이버시
##### 보안 프레임워크
- NIST Cyversecurity Framework(NIST CSF)
  - 미국 국립표준기술연구소(NIST)에서 개발한 프레임워크, 사이버 보안 지침 제공
  - 식별, 보호, 담지 대응, 복구
- 회복탄력성
- BCP/DRP: 업무연속성/재해복구계획
- ISO/IEC 27001
  - 조직의 정보보호를 체계적으로 관리/지속적으로 개선할 수 있는 프레임워크
  - 정보보호관리체계(ISMS) 표준
- ISMS-P
  - 조직의 주요 정보자산을 보호하기 위해 정보보호관리 절차와 과정을 체계적으로 수립하여 지속적으로 관리/운영하기 위한 종합적인 체계

### API 보안 가이드
### 실습
- 개인정보처리 시스템 흐름도 작성
### 요약자료
- 
</details>

# 2일차(2024/12/17)
<details>
  
  ### 클라우드 환경의 정보보안
  - VPC 주요 보안 정책: NACL(Network Access Control List)
  - ANFW vs SG vs NACL vs WAF vs Shield
</details>

# 3일차(2024/12/18)
<details>

  ### 사이버침해사례분석
  - APT 공격
  ### 보안제품기본개념과기능
  - 침입방지 시스템(IPS)
    :Firewall,IDS, Virus Worm 및 유해 사이트 차단(Contents Filtering) 시스템등이 유기적으로 통합
되어공격의탐지및방어를동시에수행하는시스템
  ### 네트워크 DLP
  - 민감한 데이터의 식별 및 보호가 네트워크를 통해 이동하는 데이터에 대해 수행
  ### 보안 제품 기본 개념과 기능
  - 웹 애플리케이션
    - 개발하는 단계에서 보안 위협 파악 및 이를 통제하여 안전한 웹페이지 개발
  ### VPN
  ### 위협 관리 시스템 TMS 이해
  ### AWS Transit Gateway 사용
  - 한 Account 에서 VPC간 통신 기술: VPC peering -> Transit Gateway
  ### TGW Migration
  ##### VPC Peering vs Transit Gateway
  
</details>

