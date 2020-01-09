"""
2019-01-09

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9.
The sum of these multiples is 23.
Find the sum of all the multiples of 3 or 5 below 1000."""

def div_by_3(number):
    s = 0
    while number:
        s += number % 10
        number //= 10
    if s % 3 == 0:
        print "3 true"
        return True
    else:
        return False


def div_by_5(num5):
    cond = ['0', '5']
    ld = str(num5)[-1]
    if ld in cond:
        print "5 true"
        return True
    else:
        return False


multiples = []

for i in range(3, 1000):
    if div_by_3(i) or div_by_5(i):
        print i
        multiples.append(i)
        
print multiples

summary = 0

for m in multiples:
    summary += m

print summary
