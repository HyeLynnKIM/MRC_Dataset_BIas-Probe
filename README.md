# mrc_dataset_probe
[AIHUB OPENLAB] 적대적 학습을 이용한 기계독해 데이터셋 편향성 분석

교차성능평가와 적대적 학습을 통한 기계독해 데이터셋의 편향성 검증

각 소스코드 파일의 용도와 기능은 다음과 같습니다.
data_augmentation: 질문 문장의 평서문화, 명사 추출, 형제어 추출
generate_queries: 추출된 형제어를 통해서 적대적 문장 생성 및 적대적 문장을 포함한 학습 및 평가 데이터 생성
krx*: KorLex 2.0 API 실행을 위한 클래스 구현
masking_utils: Mask Language Model을 이용하여 추출된 형제어들의 확률 계산 및 확률이 높은 형제어 선택
squad_utils: 기계독해 데이터 생성에 필요한 함수 모음(KorQuAD에서 제공되는 코드를 수정)

![image](https://user-images.githubusercontent.com/11895148/200234942-2b5f2d55-aa24-40b9-90ab-4553a22e2bca.png)


* 본 프로젝트는 [2022 AI 데이터 품질 개선 오픈랩 프로그램]을 통해서 진행되었습니다.
