# Percen
확률 알고리즘을 도와주는 라이브러리입니다.

## Install
```py
pip install percen
```

## How to Use
### #1-General
```py
from percen import percen

percen = Percen()
print(percen.general(#input percentage : int))
# input percentage에 50을 넣으면 50%의 확률로 True를 반환합니다.
```

### Output
```py
>> True or False
```
### #2-Detail
```py
from percen import percen

percen = Percen()
print(percen.detail(#input percentage : int))
# input percentage에 50을 넣으면 50%의 확률로 True를 반환합니다.
```
### Output
```py
{
  'result': False, #결과값
  'percentage': '50%', #입력한 확률
  'check_number': 52 #비교한 숫자(percentage > check_number이면 True를 반환)
}
```
