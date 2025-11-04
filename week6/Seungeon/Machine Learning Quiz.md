# Machine Learning Quiz
---

### Q1

당신은 딥러닝을 사용하여 텍스트를 실제 같은 음성으로 변환하기 위해 Amazon Transcribe를 사용해야 한다.

- ❌True
- ✅False

> Amazon Transcribe = 음성 → 텍스트
> 
> 
> Amazon Polly = 텍스트 → 음성
> 

---

### Q2

회사는 음성을 텍스트로 변환하고 고객의 의도를 인식하는 챗봇을 구현하고자 한다. 어떤 서비스를 사용해야 하는가?

- Transcribe
- Rekognition
- Connect
- ✅ **Lex**

---

### Q3

당신은 이미지와 비디오에서 객체, 사람, 텍스트 또는 장면을 찾고 싶다. 어떤 AWS 서비스를 사용해야 하는가?

- ✅ **Rekognition**
- Polly
- Kendra
- Lex

---

### Q4

스타트업은 빠르게 맞춤형 사용자 경험을 만들고 싶어 한다. 어떤 AWS 서비스가 도움이 되는가?

- ✅ **Personalize**
- Kendra
- Connect

---

### Q5

연구팀은 자연어 처리(NLP)를 사용하여 기사를 주제별로 그룹화하고 싶어 한다. 어떤 서비스를 사용해야 하는가?

- Translate
- ✅ **Comprehend**
- Lex
- Rekognition

---

### Q6

회사는 문서를 자연스럽고 정확한 문장으로 여러 언어로 번역하고 싶다. 무엇을 사용해야 하는가?

- Transcribe
- Polly
- ✅ Translate
- ❌ WordTranslator

> WordTranslator는 존재하지 않는 서비스
> 
> 
> AWS 번역 서비스 = **Amazon Translate**
> 

---

### Q7

개발자는 머신러닝 모델을 빠르게 구축, 학습 및 배포하고자 한다. 어떤 서비스를 사용할 수 있는가?

- ✅ **SageMaker**
- Polly
- Comprehend
- Personalize

---

### Q8

어떤 AWS 서비스가 음성을 텍스트로 쉽게 변환할 수 있게 하는가?

- Connect
- Translate
- ✅ **Transcribe**
- Polly

---

### Q9

다음 중 머신러닝 기반 문서 검색 서비스는 무엇인가?

- Translate
- ❌ Comprehend
- ✅ **Kendra**
- Polly

> Amazon Kendra = 문서 검색 엔진
> 
> 
> Amazon Comprehend = NLP 텍스트 의미 분석 → 검색 기능 아님
> 

---

### Q10

회사는 전 세계 고객이 사용하는 이미지 및 비디오 공유 플랫폼을 운영 중이다. 고객들은 최근 플랫폼에서 부적절한 콘텐츠가 보인다고 불평하고 있으며, 이를 자동으로 감지하고 일정 신뢰도 기준으로 플래그 처리하며 수동 검토가 가능해야 한다. 어떤 AWS 서비스가 적합한가?

- Polly
- Translate
- Lex
- ✅ **Rekognition**

---

### Q11

온라인 의료 회사가 Amazon Connect와 Amazon Lex를 사용하여 전화 예약과 결제를 처리하고 있다. 모든 통화는 검토를 위해 녹음되어야 하지만 저장 전에 개인식별정보(PII)를 제거해야 한다. 어떤 서비스를 사용해야 하는가?

- ❌Polly
- ✅Transcribe
- Rekognition
- Translate

> Amazon Transcribe Call Analytics = 통화 녹취 중 **PII 자동 마스킹 기능**
> 
> 
> Polly = 텍스트 → 음성, PII 처리 없음
> 

---

### Q12

Amazon Polly는 텍스트를 음성으로 변환한다. 두 가지 중요한 기능이 있다.

- 첫 번째는 단어의 발음을 사용자 지정할 수 있게 해 준다 (예: "Amazon EC2" → "Amazon Elastic Compute Cloud")
- 두 번째는 단어를 강조하고, 숨소리, 속삭임 등을 포함하도록 해 준다

올바른 조합은 무엇인가?

- ❌ Speech Synthesis Markup Language (SSML), Pronunciation Lexicons
- Pronunciation Lexicons, Security Assertion Markup Language (SAML)
- ✅ Pronunciation Lexicons, Speech Synthesis Markup Language (SSML)
- Security Assertion Markup Language (SAML), Pronunciation Lexicons

> **Pronunciation Lexicons** = 발음 제어
> 
> 
> **SSML** = 감정/강조/속삭임/호흡 제어
> 

---

### Q13

의료 회사는 의사 노트, 임상 시험 보고서 및 영상 보고서와 같은 비정형 의료 텍스트에서 정보를 탐지, 추출 및 분석하려고 한다. 이 문서는 S3에 저장된다. 솔루션은 보호 건강 정보(PHI)를 식별하여 HIPAA 준수를 충족해야 한다. 어떤 서비스를 사용해야 하는가?

- ✅ **Comprehend Medical**
- Rekognition
- Polly
- Translate
