# 7. 사전 학습 모델

마지막으로 사전 학습 (Pretrained) 모델과 미세 조정 (Fine-tuned) 학습에 대해서 알아보도록 합시다.

여기서 활용하는 모델은 BERT라는 모델과 GPT2라는 모델을 활용합니다.

## 실습 자원

본 장에서 활용하게 될 모델과 데이터 셋 입니다.

### 모델

- [Huggingface의 Transformers 라이브러리 도큐먼트](https://huggingface.co/transformers/)
- [구글 공식 BERT 깃허브 저장소](https://github.com/google-research/bert)
- [Ko-GPT2 모델 깃허브 저장소](https://github.com/SKT-AI/KoGPT2)


### 데이터

- [KorNLU Dataset](https://github.com/kakaobrain/KorNLUDatasets)
- [Naver NLP Challenge Dataset](https://github.com/naver/nlp-challenge)
- [KorQuAD 1.0](https://korquad.github.io/KorQuad%201.0/)

## 실습 내용

### 모델 실습을 위한 데이터 분석

- [KorNLI 데이터 분석](./7.2.2.KorNLI_EDA.ipynb)
- [KorNER 데이터 분석](./7.2.3.NER_EDA.ipynb)
- [KorSTS 데이터 분석](./7.2.4.KorSTS_EDA.ipynb)
- [KorQuAD 데이터 분석](./7.2.5.KorQuAD_EDA.ipynb)

### 버트를 활용한 모델 실습
- [버트를 활용한 한국어 텍스트 분류 모델](./7.2.1.bert_finetune_NSMC.ipynb)
- [버트를 활용한 한국어 자연어 추론 모델](./7.2.2.bert_finetune_KorNLI.ipynb)
- [버트를 활용한 한국어 개체명 인식 모델](./7.2.3.bert_finetune_NER.ipynb)
- [버트를 활용한 한국어 텍스트 유사도 모델](./7.2.4.bert_finetune_KorSTS.ipynb)
- [버트를 활용한 한국어 기계 독해 모델](./7.2.5.bert_finetune_KorQuAD.ipynb)

### GPT2를 활용한 모델 실습
- [GPT2를 활용한 한국어 언어 생성 모델](./7.4.1.gpt2_finetune_LM.ipynb)
- [GPT2를 활용한 한국어 텍스트 분류 모델](./7.4.2.gpt2_finetune_NSMC.ipynb)
- [GPT2를 활용한 한국어 자연어 추론 모델](./7.4.3.gpt2_finetune_KorNLI.ipynb)
- [GPT2를 활용한 한국어 텍스트 유사도 모델](./7.4.4.gpt2_finetune_KorSTS.ipynb)