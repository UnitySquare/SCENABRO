# 멋쟁이사자처럼 AI SCHOOL 9th FINAL PROJECT
2023.12.21~2024.02.05

RNN을 이용한 시나리오 제작 시뮬레이터

Hugging Face - Transformer model +  Google Colab Server + Streamlit
한정적인 컴퓨팅 자원의 문제로 코랩 환경에서 서버를 두고 스트림밋으로 서비스 구현

- 선택지 생성(pko-t5-base: Naver Serieson Crawling Dataset 으로 Fine-Tuning)
- 요약(text_summarization: T5 Small)
- 장르예측(distilbert-base-uncased-finetuned-movie-genre: NLP 다중 라벨 분류)
- 그림 생성(dreamshaper-7 + lcm-lora-sdv1-5: Stable Diffusion v1-5 에서 미세 조정된 모델)
총 4가지 모델 결합하여 서비스의 완성도를 높임
