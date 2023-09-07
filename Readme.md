

# 8 그래프 만들기
```python
import seaborn as sns

#그래프 만들기
sns.scatterplot(data = mpg, x = 'displ', y = 'hwy')

# 범위지정
sns.scatterplot(data = mpg, x = 'displ', y = 'hwy') \
   .set(xlim = [3, 6], ylim = [10, 30])
```
.