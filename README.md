1. reservoir 구축(ESN처럼, RNN에 있는 식과 동일한지 확인)
2. input 연결, readout(우선 DNN부터, 그 다음 가능하면 CNN)
3. data processing
   - non time-series : 2D mnist
   - time-series : 시간에 따른 co2 배출량 변화(from odiac)
4. reservoir를 변화시키면서 결과 비교
