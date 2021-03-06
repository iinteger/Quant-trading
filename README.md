  # Quant-traiding

파이썬으로 구현하는 퀀트 투자 책을 읽고 정리한 레포지토리입니다.

## 기록

* 영업이익과 당기수익률의 상태를 기준으로 [흑자지속, 적자지속, 흑자전환, 적자전환] 네가지의 상태로 분류
  
  * 두 지표 모두 흑자전환 - 적자전환 - 흑자지속 - 적자지속 순서로 높은 수익률을 기록함
  * 하나의 상태를 타겟으로 잡고 연단위로 리밸런싱하여 투자한 결과, 최종 수익률은 위와 동일하지만 특정 년도에서 적자지속 기업의 수익률이 가장 높은 경우가 있음. 이는 적자가 지속되어 낮아진 주가로 인한 시세차익으로 예상됨

<div>
</div>

* 부채비율, 매출액 증가율, 영업이익 증가율, 당기순이익 증가율은 수익률과 선형적인 관계가 없음

<div>
</div>

* 배당을 하지 않는 기업에 투자하는 경우가 배당을 하는 기업에 투자하는 경우보다 높은 수익률을 기대할 수 있음. 배당을 하는 기업에 투자할 경우, 주가 대비 배당률이 높은 기업에 투자하는 것이 낮은 기업에 투자하는것보다 높은 기대수익률과 안정성을 보임

<div>
</div>

* PER이 낯은 기업에 투자하는 경우가 보다 높은 수익률을 기대할 수 있으며, 소프트웨어 직군에서 상관관계가 강해지는 경향을 보임. ROE와 ROA는 예상과 다르게 수치가 낮은 산업군에서 더 높은 수익률을 보였으며, 이 또한 특별한 상관관계를 찾을 수 없었음

<div>
</div>

* 골든크로스가 발생했을때 매수해서 데드크로스가 발생했을때 매도하는 전략은 단순히 바이앤홀드 하는 전략보다 뒤떨어짐. 이동평균선 기간과 무관하게 모든 경우에서 바이앤홀드 전략이 압도적으로 더 높은 수익률을 보였음

<div>
</div>

* 정배열 시작에 매수하고 정배열 종료에 매도하거나 역배열 시작에 매도하는 전략 모두 결과가 좋지 못했음

<div>
</div>

* 상승장악형, 하락장악형, 적삼병, 흑삼병, 샛별형의 캔들 패턴이 발생해도 예상과 다른 결과가 나타나는 경우가 많았음 

<div>
</div>

* 상승 모멘텀에 매수하여 하락 모멘텀에 판매하는 전략의 경우, 모멘텀이 작은 기업에 투자하는 경우가 큰 기업에 투자하는 경우보다 높은 수익률을 달성했음

<div>
</div>

* DMI(방향성 지수)와 ADX의 경우, DMI만 사용했을때는 과반이 손실이고 평균 수익률도 0에 가까웠지만, ADX를 포함해서 투자하였을 때 수익률이 살짝 개선되었음

<div>
</div>

* 엔빌로프를 사용하여 지지선 매수-저항선 매도를 한 경우, 모든 경우에서 평균 수익률이 높았으며, a값을 높게 설정할수록(이평선과 거리를 크게 설정할수록) 수익률이 큰 폭으로 높아졌음

<div>
</div>

* 주가와 거래량의 상관관계를 나타낸 EOM 지수는 투자에 유의미하지 않았음

<div>
</div>

* RSI가 0.3 이하일때 매수, 0.7 이상일때 매도하는 전략은 평균과 중위수 모두 양수로 유의미한 결과를 보였으며, 기준일수가 길어질수록 수익률도 높아졌음. 그러나 0.5를 기준으로 한 매매는 결과가 좋지 않음

<div>
</div>

* RSI에 거래량이 포함됨 MFI를 사용한 매매 역시 RSI와 유사하지만 수익률은 약간 낮음. 그러나 편차치도 낮아서 보다 안정적으로 수익을 얻을 수 있음

<div>
</div>

* 주가가 하락한 뒤 매수하는 평균 회귀 전략을 사용한 결과, 대부분의 경우에서 과반 이상이 수익을 얻음
