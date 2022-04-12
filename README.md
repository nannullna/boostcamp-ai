# boostcamp-ai
Naver Boostcamp AI-tech Repo List

## Image Classification Competition [Link](https://github.com/nannullna/image-classification-level1-21)

마스크 착용 여부와 더불어 나이, 성별을 맞추는 분류 대회입니다. 얼굴 트래킹을 위해 학습된 MTCNN weight의 재사용 가능성을 연구했으며, EfficientNet을 앙상블하여 구체적 모델 성능 향상에 기여했습니다.

## KLUE - Relation Extraction Competition [Link](https://github.com/nannullna/klue-level2-nlp-05)

업스테이지 공개한 한국어 이해 평가(KLUE) 벤치마크 데이터셋 중 문장의 엔티티의 속성과 둘 사이의 관계를 예측하는 관계추출 태스크 대회입니다. T5를 중점으로 다양한 classification head를 구현하고, fastText를 이용해 EDA SR를 구현했으며, 팀 베이스라인 코드를 작성했습니다.

## Machine Reading Comprehension - Open-Domain Question Answering [Link](https://github.com/nannullna/mrc-level2-nlp-05)

단순한 추출 혹은 생성 요약 기반의 질의응답 태스크를 넘어, 정답이 포함된 지문이 주어지지 않은 채로 방대한 passage에서 정답이 담긴 지문을 추출(retrieve) 후 QA 태스크를 수행합니다. 베이스라인 구축 및 추상화/모듈화를 담당했고, RNN 기반의 custom 모델과 Hugging Face의 Trainer를 변형하여 레이어를 freeze하도록 했습니다. 최종적으로 한국어 특성을 반영한 규칙 기반의 최종 앙상블 기법을 통해 EM이 향상되었습니다.

## 귀가노니 - 출퇴근길에 듣는 인공지능 팟캐스트 [Link](https://github.com/nannullna/final-project-level3-nlp-05)

뉴스를 크롤링하여 그 중 핵심 토픽을 선정하여, 요약된 기사문을 TTS 기술을 이용해 귀로 들을 수 있느 서비스로, 모델 구현부터 배포 및 서비스 측면까지 고려된 프로젝트입니다. 단일 모델을 이용해서 추출 및 생성 요약을 수행하는 EasyBART 모델을 제안 및 구현해 서비스의 핵심 부분을 완성했습니다.
