# trade-clustering-analysis
국가 무역구조 클러스터링 프로젝트

데이터: UN Comtrade × World Bank (161개국 × 18변수)

파이프라인: K-Means → DBSCAN → RF/SVM → Bootstrap ARI

결과: 5개 무역구조 유형 도출 (SVM 교차검증 91.9%)
