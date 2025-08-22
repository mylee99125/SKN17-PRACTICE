# SKN17-PRACTICE

### 1. 사용 모델 및 데이터셋
#### - 모델: Facebook의 FastText (cc.ko.300.bin)
단어를 수치적인 표현, 즉 **벡터(Vector)**로 변환하는 '워드 임베딩(Word Embedding)' 모델입니다.

#### - 데이터셋: Common Crawl
모델이 학습한 데이터로, 수십억 개의 웹페이지에서 수집된 방대한 텍스트 데이터입니다. 모델은 이 데이터를 통해 단어의 의미와 단어 간의 관계를 학습했습니다.

#### - Direct Download (Korean)
https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.ko.300.bin.gz 
-> 압축 해제 후 cc.ko.300.bin 파일 사용

<br>

### 2. 단어 유추 원리
이 게임은 단어를 벡터 공간의 한 점으로 보고, 벡터 간의 수학적 연산을 통해 관계를 추론합니다.


<img width="382" height="257" alt="image" src="https://github.com/user-attachments/assets/013398e1-d573-4d74-a440-53264b5a7dd1" />
