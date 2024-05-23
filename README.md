punkty = 0
for i in range(5):
   print('podaj liczbe punktów z rundy', i + 1)
   punkty += int(input())
if punkty > 50 :
    print("wygrana z iloscią", punkty , "punktow. Wygrywasz magiczną nagrode :D" )
else: 
    print ("przegrana, smuteczek")
