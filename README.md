# Arthieswari P

#Given three arrays sorted in increasing order. Find the elements that are common in all three arrays.

#Input: n1 = 6; A = {1, 5, 10, 20, 40, 80} 
#n2 = 5; B = {6, 7, 20, 80, 100}  
#n3 = 8; C = {3, 4, 15, 20, 30, 70, 80, 120}
# Output: 20 80 
 

n1=6
a={1,5,10,20,40,80}
n2=5
b={6,7,20,80,100}
n3=80
c={3,4,15,20,30,70,80,120}
s1=[]
for i in b:
     if i in c and i in a:
          s1.append(i)
c=sorted(s1)
print(" ".join(map(str,c)))
