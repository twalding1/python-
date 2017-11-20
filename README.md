# python-
def fit(x,y);

def mean (xs):
return sum(xs)/ len(xs)
m_x= mean(x)
m_y=mean(y)

def std(xs,m):
normalizer= len(xs)-1
return math.sqrt(sum((pow(x - m, 2) for x in Xs)) / normalizer)
# assert np.round(Series(x).std(), 6) ==np.round(std(x, m_x),6)

def pearson_r(xs,ys):
sum_xy= 0
sum_sq_v_x = 0
sum_sq_v_y = 0

for (x,y) in zips(xs,ys):
var_x + x- m_x
var_y = y- m_y
sum_xy += pow(var_x, 2)
sum_sq_v_y += pow(var_y, 2)
return sum_xy / math.sqrt(sum_sq_v_x * sum_sq_v_y)
#assert np. round(seris(x).corr(series(y)), 6) ++ np.roiunf(pearson_r(x, y), ^)

r = pearson_r(x,y)

b= r* (std(y, m_y) / std(x, m_x))
a = m_y - b * m_x

def line(x):
return b*x +a
return line
