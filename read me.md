# 건전한 온라인 커뮤니케이션 문화 조성을 위한 악성댓글 필터링 봇



* 훈련 과정: 서비스 산업 데이터를 활용한 빅데이터 분석 실무
* 훈련 직종: 빅데이터 분석 (20010105)
* 훈련 기간: 2020.07.10 ~ 2020.12.23 (920시간)
* 팀 명: 악!플원정대
* 팀 원: 김선림, 김한준, 윤선영, 이재원, 최가은, 최호진
* 파이널프로젝트 최우수상 수상





악성 댓글 필터링 봇은 4단계 과정을 거쳐 개발됐습니다.

1) 인스타그램, 에브리타임 등 소셜 미디어와 웹사이트에서 약 12만 7천 개의 댓글 크롤링
2) 수집한 댓글을 명백한 악성 댓글은 2, 애매한 댓글은 1, 일반 댓글은 0으로 라벨링 및 토큰화
3) 1D-CNN 기반의 딥러닝 모델 학습, 0.976891의 AUC score 기록
4) Django를 이용해 악성 댓글 필터링 봇을 적용한 소셜 미디어 형식의 Web 구현, AWS의 Deep Learning AMI (Ubuntu 18.04) Version 38.0 을 이용해 배포

