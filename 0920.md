- 👋 Hi, I’m @rryug
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
rryug/rryug is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

CUTLINE = 70
name1 = '이강인'
middle = 76
final = 63.5
report = 100
total = middle + final + report
avg = total / 3

print ("---------------------")
print("이름:", name, "\t평균:", avg)
if avg >= CUTLINE:
    print('합격!\n 축하합니다.')
else :
    print('불합격! 더 노력하세요')
    print(CUTLINE-avg, '점이 부족합니다')

print('-----------------------')

n1 = 1234 ; n2 = -365

print("%d %d" % (n1, n2))
print("%+6d %+6d" % (n1, n2))
print("%-6d %-6d" % (n1, n2))


name = input('이름은?') 
eng = int(input('영어 성적은?')) 
math = int(input('수학 성적은?')) 
total =eng + math;
avg = total /2 
print('이름은:%s,총점은:%d, 평균은: %d'%(name, total,avg)) 

name = input('이름은?') 
eng = int(input('영어 성적은?')) 
math = int(input('수학 성적은?')) 
total =eng + math;
avg = total /2 
print('이름\t\t영어\t수학\t총점\t평균')
print('%s\t\t%3d\t%3d\t%3d\t%2f' % (name,eng,math,total,avg))
