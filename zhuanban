# coding=gbk
zhuanbanlist=[]
shibie=True
while shibie==True:
 print('The present people:')
 for x in zhuanbanlist:
  print(x) 
 shuru=input('\nWhich kind of operation do you want to perform？e for exit，a for add，or r for reduce\n')
 if shuru=='e':
  shibie=False
 elif shuru=='a':
  num=input('insert which position\n')
  realnum=int(num)-1
  name=input('input new member\'s name\n')
  zhuanbanlist.insert(realnum,name)
 elif shuru=='r':
  if len(zhuanbanlist)==0:
   print('There are no people,you can reduce nothing,error！')
   shibie=False
  else:
   renum=int(input('reduce which position？\n'))
   realrenum=renum-1
   zhuanbanlist.pop(realrenum)
