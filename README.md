# 这是一篇正经严肃活泼的自我介绍


我会的语言有`python`,'css','javscript'，不信写一段你看看：

```python
print('Interest Calculator:')
amount = float(input('Principal amount ?'))
roi = float(input('Rate of Interest ?'))
years = int(input('Duration (no. of years) ?'))
total = (amount * pow(1 + (roi/100), years))
interest = total - amount
print('\nInterest = %0.2f' %interest)
```