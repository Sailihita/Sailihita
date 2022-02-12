Gg=700
Bg=900
Ss=70
Paste=60
Fc=50
cname=input('enter customer name:')
cphnno=input('enter customer phnno:')
Ggq=int(input('enter no of greengram packets'))
Bgq=int(input('enter no of Blackgram packets'))
Ssq=int(input('enter no of soaps'))
Pasteq=int(input('enter no of paste'))
Fcq=int(input('enter no of face cream packets'))
bc=input('enter bill code')
bill=(Gg*Ggq)+(Bg*Bgq)+(Ss*Ssq)+(paste*pasteq)+(Fc*Fcq)
if bill>=5000:
    dis=bill*10/100
    tax=bill*10/100
elif bill>=3000:
    dis=bill*8/100
    tax=bill*10/100
elif bill>=2000:
    dis=bill*5/100
    tax=bill*10/100
elif bill>=1000:
    dis=bill*3/100
    tax=bill*10/100
else:
    print('invalid bill code')
mainbill=bill-dis+tax
print('bill amount:',mainbill)



Output:-
enter customer name:likhita 
enter customer phnno:9494925369
enter no of greengram packets8
enter no of blackgram packets7
enter no of soaps5
enter no of pastes9
enter no of face cream packets4
enter bill code3000
bill amount: 10960.0
