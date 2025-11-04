# AWS Machine Learning

### **Question 1**

한 스타트업이 빠르게 **사용자 맞춤형 경험(customized user experiences)**을 만들고 싶어 합니다.
이때 어떤 AWS 서비스가 도움이 될까요?

* **Personalize** ✅
* **Kendra**
* **Connect**

---

### **Question 2**

한 개발자가 **머신러닝 모델을 빠르게 만들고, 학습시키고, 배포하고 싶어** 합니다.
이때 사용할 수 있는 AWS 서비스는 무엇일까요?

* **SageMaker**✅
* **Polly**
* **Comprehend**
* **Personalize**

---

### **Question 3**

다음 중 **음성을 텍스트로 변환(speech-to-text)**하기 쉽게 해주는 AWS 서비스는 무엇일까요?

* **Connect**
* **Translate**
* **Transcribe** ✅
* **Polly**

---

### **Question 4**

한 온라인 의료회사가 있습니다.
이 회사는 전화로 의사 예약을 받는 시스템을 운영 중이며,
**Amazon Connect**와 **Amazon Lex**를 사용해 통화, 예약, 결제 과정을 자동화하고 있습니다.

회사의 정책상 모든 통화는 저장되어야 하지만,
저장 전에 **개인 식별 정보(PII)**를 반드시 제거해야 합니다.
이때, 통화 내용에서 PII를 제거하는 데 사용할 수 있는 서비스는 무엇일까요?

* **Amazon Polly** 
* **Amazon Transcribe** ✅
* **Amazon Rekognition**
* **Amazon Translate**

---

### **Question 5**

**Amazon Polly**는 텍스트를 음성으로 바꿔주는 서비스입니다.
이 서비스에는 두 가지 주요 기능이 있습니다.

1️⃣ 첫 번째는 **단어 발음을 직접 정의해 커스터마이징할 수 있는 기능**입니다.
예를 들어 “Amazon EC2”를 “Amazon Elastic Compute Cloud”처럼 읽도록 조정할 수 있습니다.

2️⃣ 두 번째는 **강조, 숨소리, 속삭임 등 자연스러운 발화 표현을 추가할 수 있는 기능**입니다.

이 두 기능에 해당하는 용어 조합으로 올바른 것은 무엇일까요?

* **Speech Synthesis Markup Language (SSML)**, **Pronunciation Lexicons**
* **Pronunciation Lexicons**, **Security Assertion Markup Language (SAML)**
* **Pronunciation Lexicons**, **Speech Synthesis Markup Language (SSML)** ✅
* **Security Assertion Markup Language (SAML)**, **Pronunciation Lexicons**

---

### **Question 6**

한 연구팀이 **자연어 처리(NLP)**를 이용해 여러 **기사(문서)를 주제별로 자동 분류(grouping)**하려고 합니다.
이때 사용할 수 있는 AWS 서비스는 무엇일까요?

* **Translate**
* **Comprehend** ✅
* **Lex**
* **Rekognition**

---

### **Question 7**

한 회사가 **음성을 텍스트로 변환하고, 고객의 의도를 인식하는 챗봇(chatbot)**을 만들고 싶어 합니다.
어떤 AWS 서비스를 사용해야 할까요?

* **Transcribe**
* **Rekognition**
* **Connect**
* **Lex** ✅

---

### **Question 8**

다음 중 **머신러닝으로 구동되는 문서 검색 서비스(document search)**는 무엇일까요?

* **Translate** 
* **Kendra** ✅
* **Comprehend**
* **Polly**

---

### **Question 9**

한 회사가 전 세계 고객을 대상으로 **이미지·영상 공유 플랫폼**을 운영하고 있습니다.
이미지와 영상은 **S3 버킷**에 저장되고, **CloudFront CDN**으로 전 세계에 배포됩니다.

최근 사용자들이 **부적절하거나 공격적인 콘텐츠가 증가했다고 불만**을 제기했습니다.
직원들이 직접 검수하기엔 너무 많은 시간과 비용이 듭니다.

이때,

* 자동으로 **부적절한 이미지·영상을 감지**하고,
* **신뢰도(Confidence Threshold)**를 기준으로 표시(플래그)하며,
* 필요 시 **수동 검토**가 가능하도록 하는
  AWS 서비스를 선택해야 합니다.

어떤 서비스가 적합할까요?

* **Amazon Polly**
* **Amazon Translate**
* **Amazon Lex**
* **Amazon Rekognition**✅

---

### **Question 10**

한 회사가 **문서를 여러 언어로 번역**하고 싶습니다.
그 번역이 **자연스럽고 정확한 표현으로 이루어지길 원합니다.**
어떤 AWS 서비스를 사용해야 할까요?

* **Transcribe**
* **Polly**
* **Translate** ✅
* **WordTranslator**

---

### **Question 11**

당신이 **이미지나 영상 속에서 사람, 사물, 텍스트, 장면 등을 자동으로 인식하고 싶을 때**,
사용해야 할 AWS 서비스는 무엇일까요?

* **Rekognition** ✅
* **Polly**
* **Kendra**
* **Lex** 

---

### **Question 12**

“**Amazon Transcribe**를 사용하면 **텍스트를 실제 사람처럼 들리는 음성으로 변환할 수 있다**.”
이 문장은 옳을까요, 그를까요?

* **True** — 참 
* **False** — 거짓 ✅

---

### **Question 13**

한 의료회사가 있습니다.
이 회사는 **의사 소견서, 임상 보고서, 방사선 진단 기록 등 비정형 의료 텍스트**를 분석하려 합니다.

이 문서들은 **S3 버킷**에 저장되어 있으며,
환자의 개인정보(Protected Health Information, PHI)를 식별해 **HIPAA 규정에 맞게 처리**해야 합니다.

이때 적절한 AWS 서비스는 무엇일까요?

* **Amazon Comprehend Medical** ✅
* **Amazon Rekognition**
* **Amazon Polly**
* **Amazon Translate**


