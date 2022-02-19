---
title: "[파이썬] itertools로 대출 상환금 계산하기"
date: 2022-01-13 13:54:11 +0900
categories: [프로그래밍, 메모]
tags: [python]
---

```python
from itertools import accumulate
# accumulate는 원하는 함수를 반복해서 누적 연산하는 제너레이터를 생성한다.

cashflows = [1000, -90, -80, -100, -120]

# 기존 balanced에 연이율 5%를 적용하고, payment를 더한다.
def loan_calc(balance, payment):
    return balance*1.05 + payment

list(accumulate(cashflows, loan_calc))
# [1000, 960.0, 928.0, 874.4000000000001, 798.1200000000001]
```

마법처럼 간단한 코드가 완성되었다.

반복 누적 연산이 필요한 모든 부분에 파이썬 itertools.accumulate를 활용할 수 있다.

출처: [파이썬 itertools 공식 도큐먼트 accumulate 챕터](https://docs.python.org/3/library/itertools.html#itertools.accumulate)
