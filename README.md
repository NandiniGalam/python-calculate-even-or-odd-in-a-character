# python-calculate-even-or-odd-in-a-character
s=input()
v="aeiouAEIOU"
vc=0
cc=0
for i in range(len(s)):
  if s[i].isalpha():
    if s[i] in v:
      vc=vc+1 
    else:
      cc=cc+1 
print(vc,cc)

#without using range
s=input()
v="aeiouAEIOU"
vc=0
cc=0
for i in s:
  if i.isalpha():
    if i in v:
      vc=vc+1 
    else:
      cc=cc+1 
print(vc,cc)      
