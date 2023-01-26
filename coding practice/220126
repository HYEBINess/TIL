# 튜플 : 함수의 가변 인자로 사용

def f(*x): # *: 인자수가 정해지지 않았음을 의미
    print(f'입력된 데이터 타입:{type(x)}')
    sum_x = 0
    product_x = 1
    for val in x:
        sum_x += val
        product_x *= val
    return sum_x, product_x

S, P = f(1, 2, 3, 4, 5)
print(S, P)
