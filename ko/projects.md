---
layout: single
author_profile: true
lang: ko
permalink: /ko/projects/
title: "프로젝트"
toc: true
toc_sticky: true
---

아래 프로젝트들은 최신순으로 정렬되어 있습니다. **참고로 밑에 링크로 연결된 문서들은 모두 영문으로 작성되어 있습니다.**

# 2026

## [디지털 병리학을 위한 딥러닝: PatchCamelyon 기반 디지털 병리 종양 탐지(Deep Learning for Digital Pathology: Tumor Detection Using the PCam Dataset)](/attachments/2026/CSE_527_Final_Report___PCam.pdf)

*2026년 3월 20일 작성 및 제출* ([링크](/attachments/2026/CSE_527_Final_Report___PCam.pdf))

<figure>
  <img src="/attachments/2026/cse_527_project_description_image.jpg">
  <figcaption>Google Gemini와 Google Nana Banana Pro를 사용하여 생성한 설명용 이미지 (시각적 이해를 돕기 위한 용도로만 사용되었으며, 프로젝트 보고서에는 포함되지 않았습니다. 이미지 내의 세포 이미지는 AI가 생성한 것으로 실제 사용된 데이터셋과는 관계가 없습니다.)</figcaption>
</figure>

이 프로젝트는 워싱턴 대학교 전기컴퓨터공학(ECE) 대학원생 사이먼 조우(Simon Zou)와 공동으로 수행하였으며, 2026년 겨울학기 [이수인 교수님](https://suinlee.cs.washington.edu/home)의 [CSE 527: 계산 생물학 - 생물학 및 생의학에서의 설명 가능한 인공지능](https://courses.cs.washington.edu/courses/cse527/) 수업의 기말 프로젝트입니다.
전이성 조직의 정확한 식별은 암 진단에 필수적이지만, 의료 시스템은 병리학자 부족이라는 심각한 문제에 직면해 있습니다. 이 문제를 해결하기 위해, 본 논문은 딥러닝 아키텍처를 활용한 조직병리 이미지에서의 종양 탐지 자동화에 초점을 맞추었습니다. 맞춤형 합성곱 신경망을 기준 등변 모델 및 사전 학습된 잔차 네트워크와 비교 평가하였습니다. 모든 모델이 높은 진단 정확도를 달성하였고, 데이터 증강을 적용한 미세 조정된 잔차 네트워크가 가장 높은 전체 정확도를 기록하였지만, 맞춤형 모델은 월등히 뛰어난 연산 효율성을 보여주었습니다. 또한, 해석 가능성 분석 결과, 맞춤형 모델은 고도로 국소화된 세포 구조에 의존하여 예측을 수행한 반면, 사전 학습된 네트워크는 더 넓은 공간적 특징에 집중하였습니다. 이러한 결과는 경량화되고 해석 가능한 목적 특화 진단 도구가 더 깊은 네트워크와 경쟁력 있는 성능을 발휘할 수 있음을 시사하며, 환자 안전을 저해하지 않으면서 임상 업무량을 완화하는 효율적인 사전 분류 솔루션을 제공합니다.

- 이 논문은 2026년 3월 12일 수업 내 포스터 세션에서도 발표되었습니다. 포스터는 아래에서 확인하거나 [이 링크](/attachments/2026/cse_527_final_poster.pdf)를 통해 접근하실 수 있습니다.

<img src="/attachments/2026/cse_527_final_poster.png" alt="포스터 미리보기 이미지">

# 2025

## [사회경제적 요인을 통제 하에 고객 잔고 및 신용 부도가 정기예금 가입에 미치는 영향(The Impact of Client Balance and Credit Default on Term Deposit Subscription, Controlling for Socioeconomic Factors)](/attachments/2025/BIOST_531_Final_Project.pdf)

*2025년 12월 9일 작성 및 제출* ([링크](/attachments/2025/BIOST_531_Final_Project.pdf))

<figure>
  <img src="/attachments/2025/BIOST_531_final_project_image.jpg">
  <figcaption>Google Gemini와 Google Nana Banana Pro를 사용하여 생성한 설명용 이미지 (시각적 이해를 돕기 위한 용도로만 사용되었으며, 프로젝트 보고서에는 포함되지 않았습니다.)</figcaption>
</figure>

이 논문은 같은 통계학 석사과정 동기인 앨리슨 웡(Alison Wong) ([LinkedIn](linkedin.com/in/asnwong), [GitHub](https://github.com/alisonsnwong))과 공동으로 작성하였으며, 2025년 가을학기 케이티 윌슨(Katie Wilson) 교수님의 [BIOST 531: 결측 데이터 분석을 위한 통계적 방법론](https://www.biostat.washington.edu/academics/courses/biost/531) 수업의 기말 프로젝트입니다. 이 연구는 포르투갈 은행의 Bank Marketing 데이터셋을 분석하여, 결측된 사회경제적 데이터를 통제하면서 연평균 잔액과 신용 채무불이행이 정기 예금 가입에 미치는 영향을 정량화하였습니다. 관측된 데이터 패턴을 기반으로 무작위 결측(MAR 또는 Missing at Random) 메커니즘을 가정하고, 완전 사례(Complete Case 또는 CC) 분석, 베이지안 우도, 다중 대입(Multiple Imputation) 방법을 활용하여 데이터셋 내 결측 데이터를 처리하였습니다. 잔액이 높을수록 가입 확률이 유의하게 증가하였으며(10,000유로당 약 26%), 신용 채무불이행은 가입 확률을 감소시키는 것으로 나타났습니다(약 38-41%). 특히, CC 분석은 다른 두 방법에 비해 채무불이행의 부정적 효과를 과대추정하여, CC 분석 사용 시 발생할 수 있는 편향 가능성을 시사합니다.

***

## [다양한 결측 데이터 조건에서의 대입 방법 평가(Evaluation of Imputation Methods Under Different Missing Data Conditions)](/attachments/2025/stat529_final_project_yehchan_yoo.pdf)

*2025년 6월 9일 작성 및 제출* ([링크](/attachments/2025/stat529_final_project_yehchan_yoo.pdf))

<figure>
  <img src="/attachments/2025/image_for_imputation_evaluation_project.png">
  <figcaption>ChatGPT로 생성하고 Google Gemini로 편집한 설명용 이미지 (시각적 이해를 돕기 위한 용도로만 사용되었으며, 최종 프로젝트 보고서 및 포스터에는 포함되지 않았습니다.)</figcaption>
</figure>

<figure>
  <img src="/attachments/2025/stat529_combined_imputation_comparison.png">
  <figcaption>프로젝트의 주요 시각화</figcaption>
</figure>

이 논문은 워싱턴 대학교에서 [로빈 메이하(Robin Meija) 교수님](https://www.biostat.washington.edu/people/robin-mejia)의 [STAT 529: 표본 조사 기법](https://stat.uw.edu/academics/course-catalog/stat-529) 수업의 기말 프로젝트로 작성되었습니다. 이 논문은 뉴욕주 2023년 1년 American Community Survey 공공 마이크로데이터 표본에서 임대료(`RNTP` 또는 rent price)와 부동산 가치(`VALP` 또는 property value) 두 변수에 대해 완전 무작위 결측(MCAR 또는 Missing Completly at Random), 무작위 결측(MAR 또는 Missing at Random), 비무작위 결측(MNAR 또는 Missing Not at Random) 세 가지 결측 데이터 조건에서 다양한 대입 방법의 성능을 시뮬레이션합니다. 각 결측 데이터 조건에 대해 대입 없음, 평균, 무작위, 최근접 이웃, 회귀 등 다섯 가지 대입 접근법을 적용하였습니다. 연구 결과, 무작위 대입법은 비무작위 결측 조건에서 가장 우수한 분위수 추정치를 제공하였으며, 평균 및 회귀 방법은 평균 추정에는 더 우수하지만 분위수를 왜곡하는 것으로 나타났습니다. 최근접 이웃 방법은 느리고 편향이 심하여 가장 효과가 낮았습니다.

- 이 논문은 2025년 6월 9일 봄 학기 워싱턴 대학교 통계·사회과학 센터(University of Washington Center for Statistics and Social Sciences) 포스터 세션에서도 발표되었습니다. 포스터는 아래에서 확인하거나 [이 링크](/attachments/2025/stat529_poster_final.pdf)를 통해 접근하실 수 있습니다.

<img src="/attachments/2025/stat529_poster_image.jpeg" alt="포스터 미리보기 이미지">

***

## [Rec-R1 재현 연구(Replication of Rec-R1)](/attachments/2025/CSE_493S_599S_Final_Project.pdf)

*2025년 6월 6일 작성 및 제출* ([링크](/attachments/2025/CSE_493S_599S_Final_Project.pdf), [Github 저장소](https://github.com/yehchanyoo/Rec-R1_magic))

<figure>
  <img src="/attachments/2025/image_for_replication_of_rec-r1_project.png">
  <figcaption>ChatGPT로 생성한 설명용 이미지 (시각적 이해를 돕기 위한 용도로만 사용되었으며, 최종 보고서에는 포함되지 않았습니다.)</figcaption>
</figure>
<figure>
  <table style="border-collapse: collapse; border: none;">
    <tr style="border: none;">
      <td style="border: none;"><img src="/attachments/2025/CSE_49ㅗㄴ3S_C4_results.png"></td>
      <td style="border: none;"><img src="/attachments/2025/CSE_493S_Beauty_results.png"></td>
    </tr>
  </table>
  <figcaption>논문의 두 시각화 (Figure 2와 Figure 3)</figcaption>
</figure>

이 논문은 워싱턴 대학교에서 [오세웅 교수님](https://homes.cs.washington.edu/~sewoong/)이 가르치시는 [CSE 493S/599S: 고급 머신러닝](https://courses.cs.washington.edu/courses/cse493s/25sp/) 수업의 기말 프로젝트로, 같은 수업을 수강한 [채정인](https://justin-chae.org), [요한 린드퀴스트 (Johan Lindqvist)](https://www.linkedin.com/in/johan-lindqvist-871a4720b/), [토마스 릴리 (Thomas Lilly)](https://foster.uw.edu/academics/degree-programs/phd-program/directory/thomas-lilly/)와 공동으로 작성하였습니다. 이 프로젝트는 대규모 언어 모델(LLM)과 추천 시스템을 결합하는 강화 학습 프레임워크를 제안한 [Rec-R1 논문](https://arxiv.org/pdf/2503.24289)의 결과를 재현하는 것을 목표로 하였습니다. 공개된 코드와 데이터셋을 사용하여, 팀원들과 함께 Rec-R1이 제품 검색 및 순차적 추천 등 여러 과제에서 모델 성능을 향상시키고, 지도 학습 미세 조정보다 범용 추론 능력을 더 잘 보존함을 검증하였습니다. 그러나 고용량 메모리 GPU 접근의 한계로 인해 논문의 연산 효율성 주장을 재현할 수 없었으며, 부실하게 문서화된 코드와 관련된 상당한 문제도 발견하였습니다. 이러한 어려움에도 불구하고, 이 프로젝트는 Rec-R1의 성능 이점을 확인하였으며, 재현성을 위한 더 나은 리소스 접근과 코드 유지보수의 필요성을 강조하였습니다.

# 2023

## [채소 소비를 기반으로 한 미국 주별 조(粗)당뇨병 유병률의 추론 및 예측(Inference and Prediction on Crude Diabetes Prevalence in U.S. States Based on Vegetable Consumption)](/attachments/2023/DATA_C102_Project_Final_Project_Submission__CD_TE_CM_YY___230512_.pdf)

*2023년 5월 12일 최종 업데이트* ([링크](/attachments/2023/DATA_C102_Project_Final_Project_Submission__CD_TE_CM_YY___230512_.pdf))

<figure>
  <img src="/attachments/2023/DATA 102 Bayesian Beta Regression graph.png">
  <figcaption>논문 내 베이지안 예측 모델의 베이지안 베타 회귀 그래프</figcaption>
</figure>

이 논문은 2023년 봄학기 [라메쉬 스라다란(Ramesh Sridharan) 강사님](https://www.linkedin.com/in/rameshsridharan/)과 [에이만 자하니(Eaman Jahani) 교수님](https://eamanjahani.com/)이 가르치시는 DATA 102: 데이터, 추론, 의사결정 수업의 기말 프로젝트로, 같은 반 동기들인 [크리스티나 덩(Christina Đặng)](https://www.linkedin.com/in/christinadang2026/), [코난 미니한(Conan Minihan)](https://www.linkedin.com/in/conanminihan/), [테츠로 에스쿠데로(Tetsuro Escudero)](https://www.linkedin.com/in/tetsuro-escudero-542a93219/)와 공동으로 작성하였습니다. 이 논문은 추론적 및 예측적 기법을 사용하여 미국 주들의 채소 소비와 조당뇨병 유병률 간의 관계를 조사하고, 채소 소비를 기반으로 당뇨병 유병률을 예측합니다.

# 2022

## [｢401(k) 가입자격 변화가 저축에 미치는 영향｣ 재현 및 개선 연구(Replication and Improvement of "How Do 401(k)s Affect Saving? Evidence from Changes in 401(k) Eligibility")](/attachments/2022/group04_YY_XZ.pdf)

*2022년 12월 16일 최종 업데이트* ([링크](/attachments/2022/group04_YY_XZ.pdf))

이 논문은 2022년 가을학기 [펑 딩(Peng Ding) 교수님](https://statistics.berkeley.edu/people/peng-ding)이 가르치시는 STAT 156: 인과 추론 수업의 기말 프로젝트로, 같은 반 동기인 [신이 지(Xinyi Zi)](https://www.linkedin.com/in/xinyi-zi/)와 공동으로 작성하였습니다. 이 논문은 [알렉산더 M. 겔버(Alexander M. Gelber) 교수](https://gps.ucsd.edu/faculty-directory/alexander-gelber.html)의 2011년 인과 추론 논문 [｢401(k) 가입자격 변화가 저축에 미치는 영향｣](https://www.aeaweb.org/articles?id=10.1257/pol.3.4.103)를 탐색, 재현, 비판, 재수행합니다.

- 비디오 발표: [https://www.youtube.com/watch?v=Tpw7Ch7XJDg&feature=youtu.be&ab_channel=XinyiZi](https://www.youtube.com/watch?v=Tpw7Ch7XJDg&feature=youtu.be&ab_channel=XinyiZi)

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/Tpw7Ch7XJDg' frameborder='0' allowfullscreen></iframe></div>

# 2019

## [SAAS x Trace Data](https://docs.google.com/presentation/d/12Q5RciThBbhEOnpQ-6ASKT7Fe_ZnnH4NoDMHMqB73cE/edit?usp=sharing)

*2019년 12월 13일 최종 업데이트* ([링크](https://docs.google.com/presentation/d/12Q5RciThBbhEOnpQ-6ASKT7Fe_ZnnH4NoDMHMqB73cE/edit?usp=sharing))

<figure>
  <img src="https://github.com/user-attachments/assets/c6ba5dac-e7f2-48a7-b3d1-bb0c0fe54b70" alt="프로젝트에서 생성된 워드 클라우드">
  <figcaption>프로젝트에서 생성된 워드 클라우드 (링크된 발표에 포함)</figcaption>
</figure>

2019년 가을학기 동안 학생 응용통계학 학회(SAAS)의 데이터 컨설팅 위원회 회원으로서, Trace Data(이후 [Netskope](https://www.netskope.com/)에 인수됨)라는 스타트업이 제공한 데이터를 활용하여 머신러닝과 자연어 처리 모델을 사용한 자체 JSON 키-값 쌍 분류 시스템을 팀으로 구축하였습니다. 구체적으로, [Amal Bhatnagar](https://www.linkedin.com/in/amal-bhatnagar/)와 함께 tf-idf를 주요 지표로 활용한 비지도 군집화 알고리즘을 개발하였습니다.

# 2018

## [사회과학에서의 확률의 의미](/attachments/2018/susa_research_yy_fall_2018.html)

*2025년 7월 13일 최종 업데이트; 원래 2018년 가을학기에 작성* ([링크](/attachments/2018/susa_research_yy_fall_2018.html))

<figure>
  <img src="/attachments/2018/image_for_meaning_of_probabilities_in_social_sciences.png">
  <figcaption>ChatGPT로 생성한 설명용 이미지. 시각적 이해를 돕기 위한 용도로만 사용되었으며, 최종 논문에는 포함되지 않았습니다.</figcaption>
</figure>

사회과학에 관심이 많은 통계학 전공자로서, 사회과학 연구에서 확률이 빈번하게 사용되는 것을 목격하였습니다. 하지만 항상 궁금했습니다: *이 확률들은 근본적으로 무엇을 의미하는가?* 통계학 학부 학생 협회(현재 SAAS, 학생 응용통계학 학회)의 연구 및 출판 위원회 활동 기간 동안 이 질문에 답하기 위해 사회과학에서의 확률의 의미에 대한 기사를 작성하였습니다.

***

## [UC Berkeley 통계학 학부생의 비통계학자와의 의사소통 준비도 분석](/attachments/2018/Yoo_Yehchan_Spring2018_CompleteResearchPaper.pdf)

*2018년 5월 9일 최종 업데이트* ([링크](/attachments/2018/Yoo_Yehchan_Spring2018_CompleteResearchPaper.pdf))

<figure>
  <img src="/attachments/2018/Statistical Communication AI-generated image.png">
  <figcaption>ChatGPT로 생성한 설명용 이미지. 시각적 이해를 돕기 위한 용도로만 사용되었으며, 최종 논문에는 포함되지 않았습니다.</figcaption>
</figure>

UC Berkeley 통계학 학부생의 비통계학자를 위한 통계적 글쓰기 준비도를 평가한 결과, 상당한 격차가 드러났습니다. 전공 수업에서 통계적 글쓰기에 대한 상당한 교육이 이루어지고 있음에도 불구하고, 학생들은 비통계학자와의 의사소통에 대한 실질적 경험이 부족하였습니다. 교수들과의 인터뷰를 통해 더 엄격한 글쓰기 요건을 시행하는 것에 대한 주저함이 있었으며, 이는 자원 제약과 프로그램 성장에 대한 기대에서 비롯된 것이었습니다. 그러나 이러한 결과는 통계학과 내 통계적 글쓰기 교육에 대한 자원 확대의 시급한 필요성을 강조합니다. 이 프로젝트는 다양한 학문 분야의 담론 관습에 관한 COLWRIT R4B 수업의 기말 프로젝트로 작성되었습니다.

***

## [지역의 안락사 합법화와 해당 지역의 자살률 사이에 통계적 관계가 있는가?](https://saas.berkeley.edu/rp/suicide)

*2018년 5월 1일 최종 업데이트* ([링크](https://saas.berkeley.edu/rp/suicide))

<figure>
  <img src="/attachments/2018/yc3.png">
  <figcaption>프로젝트의 시각화, 1969년에서 2012년 사이 노르웨이(안락사를 합법화하지 않음)와 네덜란드(안락사를 합법화함)의 자살률 추세를 비교</figcaption>
</figure>

멕시코의 데이터를 이용한 통계 분석에 따르면, 특정 멕시코 지역에서의 소극적 안락사 합법화는 단기적으로 해당 지역의 조자살률과 관련이 없는 것으로 보입니다. 네덜란드(그리고 노르웨이)의 데이터에 대한 이중차분 분석에 따르면, 적극적 및 소극적 안락사 합법화를 향한 주요 사건들이 네덜란드의 조자살률에 단기적으로 감소 효과를 미쳤을 수 있지만, 그 효과는 시간이 지남에 따라 희석된 것으로 보입니다. 이 연구 기사는 통계학 학부 학생 협회(현재 SAAS, 학생 응용통계학 학회)의 연구 및 출판 위원회 활동 기간에 작성되었습니다.
