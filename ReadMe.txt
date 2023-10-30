인공지능론 Term Project
							2018100922 이승건
============================================================

1. 최종보고서 PPT 
[최종보고서] 폴더 내 첨부되어 있습니다.

2. 데이터
1) [ETL] 폴더
ETL 문자 데이터베이스입니다. 
이 중 ETL8G만 사용하여 이를 첨부하였습니다.

2) [library] 폴더
ETL 데이터베이스에서 데이터를 수집하기 위한 local library입니다.

3) [japanese-family-names-master] 폴더
추후에 한자를 히라가나로 변환하기 위한 데이터가 포함되어 있습니다.

4) [data] 폴더
ETL 데이터베이스에서 추출한 x_train, x_test, y_train, y_test, y_train_char 데이터가 포함되어 있습니다.

5) [model] 폴더
학습된 모델 파일이 저장되어 있습니다.

6) [japanese_use_firstname] 폴더
모델을 직접 사용하기 위한 각 이름에 대한 손글씨 데이터가 들어있습니다.

3. 프로그램
1) CNN_japanese.ipynb
데이터를 추출하고 전처리과정 진행, 모델 학습을 진행하는 프로그램입니다.

2) CNN_japanese_use.ipynb
학습된 모델을 직접 사용하는 프로그램입니다.
