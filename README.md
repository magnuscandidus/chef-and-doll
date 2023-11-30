# chef-and-doll
# cook your dish here
for i in range(int(input())):
    n = int(input())
    list=[]
    for i in range(n):
        list.append(int(input()))
    list1 = set(list)
    for j in list1:
        if list.count(j)%2 != 0:
            print(j)
        
