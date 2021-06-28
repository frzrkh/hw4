person={}
imena=list()
vozrast=list()
pol=list()
while True:
        n=input('введи имя ')
        imena.append(n)
        if n=='0':
                break
        a=input('введи свой возраст ')
        vozrast.append(a)
        s=input('укажи свой пол ')
        pol.append(s)
        d={'name':imena, 'age':vozrast, 'sex':pol}
        person.update(d)
for i in person.values():
        print(i, end=' ')
