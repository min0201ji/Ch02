# Ch02
Ch1-5

2_1_Variable
"""
#날짜 : 2021/04/05
#이름: 박민지
#변수(variable)
# -데이터를 처리하기 위한 메모리 공한
-데이터를 처리하기 위한 데이터 그릇
"""
var1 =1
var2 = 2
result = var1 + var2
print('result :', result)

2_2_dataType
"""
날짜 : 2021/04/05
이름: 박민지
내용 : 파이썬 자료형(데이터 타입) 실습 교재 p37
"""

#숫자형(int)
var1 = 1
var2 = 2
var3 = -3

print('var1 :', var1)
print('var2 :', var2)
print('var3 :', var3)
print('var1 type :', type(var1))
print('var2 type :', type(var2))
print('var3 type :', type(var3))

#실수형(float)
var4 = 0.4
var5 = -1.213

print('var4 :', var4)
print('var5 :', var5)
print('var4 type :', type(var4))
print('var5 type :', type(var5))

#논리형(bool)
var6 = True
var7 = False

print('var6 :', var6)
print('var7 :', var7)
print('var6 type :', type(var6))
print('var7 type :', type(var7))

#문자열(string)
var8 = 'A'
var9 = 'Apple'
var10 = "Apple"
var11 = "사과"
print('var8 :', var8)
print('var9 :', var9)
print('var10 :', var10)
print('var11 :', var11)
print('var8 type :', type(var8))
print('var9 type :', type(var9))
print('var10 type :', type(var10))
print('var11 type :', type(var11))

2_3_Operator
"""
날짜 : 2021/04/05
이름: 박민지
내용 : 파이썬 연산자 실습 교재 p38
"""
#대입연산자
a = 1
b = c = d = 0
e, f, g = 7, True, 'Apple'

print('a :', a)
print('c :', c)
print('f :', f)
print('g :', g)

#산술연산자
num1= 1
num2= 2
num3, num4= 3, 4

r1 = num1 + num2
r2 = num1 - num2
r3 = num2 * num3
r4 = num4 / num2
r5 = num4 // num2
r6 = num4 % num3
r7 = num3 ** num2

print('r1 :', r1)
print('r2 :', r2)
print('r3 :', r3)
print('r4 :', r4)
print('r5 :', r5)
print('r6 :', r6)
print('r7 :', r7)

#복합대입연산자/(관계연산자)
num5, num6, num7, num8 = 5, 6, 7, 8

num5 += 1 #num5 = num5 +1
num6 -= 2 #num6 = num6 - 2
num7 *= 3 #num7 = num7 * 3
num8 /= 4 #num8 = num8 / 4

print('num5 :', num5)
print('num6 :', num6)
print('num7 :', num7)
print('num8 :', num8)

#비교연산자
var1 = 1
var2 = 2

rs1 = var1 > var2
rs2 = var1 < var2
rs3 = var1 >= var2
rs4 = var1 <= var2
rs5 = var1 == var2
rs6 = var1 != var2

print('rs1 :', rs1)
print('rs2 :', rs2)
print('rs3 :', rs3)
print('rs4 :', rs4)
print('rs5 :', rs5)
print('rs6 :', rs6)

#논리연산자
var3 = 3
var4 = 4

res1 = var3 > 2 and var4 > 3 #교집합
#       True & True = True(res1)
res2 = var3 > 2 and var4 > 4 #교집합
#         True & False = False(res2) 둘다 참이 여야지 전체가 참, 하나라도 거짓이면 거짓
res3 = var3 > 2 or var4 > 4 #둘중에 하나만 참이여도 참, 합집합
res4 = var3 > 4 or var4 > 5 #둘중에 하나만 참이여도 참, 합집합
res5 = not var3 > var4 #var3은 var4보다 크지 않다, 않다(=not)


print('res1 :', res1)
print('res2 :', res2)
print('res3 :', res3)
print('res4 :', res4)
print('res5 :', res5)

2_4_IOTest
"""
이름 : 박민지
날짜 : 2021/04/06
내용 : 파이썬 표준 입출력 실습 교재 p.42
"""

#파이썬 표준입력장치
#num = input('숫자입력 : ') #함수
#print("입력한 숫자 :", num)
#print('num type :', type(num))
#print('num + 1:', num+1) #num+1 에서 num이 숫자가 아니기 때문에 오류남

#입력받은 문자열을 숫자로 변환
#result = int(num) #result가 숫자 / 숫자일 경우 int를 써서 변환해야된다
#print('result :', result)
#print('result type :', type(result))
#print('result + 1 :', result+1)

#파이썬 표준출력장치
#print('hello', end=',')
#print('python')

#서식문자열 출력
print('%d년 %d월 %d일 %s요일' % (2021, 4, 6, '화')) #%d 는 서식문자/ d=decimal(숫자) s=string(문자)

#sep(erate) 옵션
#print('010', '1234', '5678', sep='-')

#포멧문자열 출력
#print('이름:{}, 나이:{}, 주소:{}'.format('박민지', '23', '부산'))

2_5_String(문자열)
"""
이름 : 박민지
날짜 : 2021/04/06
내용 : 파이썬 표준 입출력 실습 교재 p.42
"""

#문자열 더하기
str1 = 'Hello'
str2 = 'Python'
str3 = str1 +str2

print('str3 :', str3)

#문자열 곱하기
name = '박민지'
result = name * 3
print('result :', result)

#문자열 길이 구하기
sample = 'Hello World'
print('sample 길이 :', len(sample))

#문자열 인덱스
print('sample 1번째 문자:', sample[0])
print('sample 7번째 문자', sample[6])
print('sample -1번째 문자', sample[-1])

#문자열 자르기
print('sample 0 ~ 5까지 문자 :', sample[0:5])
print('sample 0 ~ 5까지 문자 :', sample[:5]) #처음부터 5까지
print('sample World 출력 :', sample[6:11])
print('sample World 출력 :', sample[6:]) #6에서 마지막까지

#문자열 분리
people = '김유신|김춘추|장보고|강감찬|이순신'
p1, p2, p3, p4, p5 = people.split('|') #splash 구분한다는 뜻 (|)

print('p1 :', p1)
print('p2 :', p2)
print('p3 :', p3)
print('p4 :', p4)
print('p5 :', p5)

#문자열 이스케이프
print('서울\n대전\n대구\n부산\n광주')
print('한국\t미국\t일본\t중국\t호주')
print('안녕하세요. \'반갑습니다.\'')
