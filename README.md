#ACM_Task_-Your-Name-
Roll No:-AM.EN.U4CSE23056
LinkedIn ID:-
Hackerrank ID:-
#Task-3
#problem 1
list=[3,2,4,6,5,7,8,0,1] 
sum=0
for i in list:
    if i % 2 != 0:
    sum = sum + i
print("sum of the list:",sum)
#problem 2
arr_count=int(input())
arr=list(map(int,input().split()))
print(sum(arr))
