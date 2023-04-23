# Calculator-for-beginners
from colorama import init
from colorama import Fore, Back, Style
init()
print( Back.RED )

rer = float(input("Введите первое число: "))
qwe = float(input("Введите второе число: "))
ded = input("Выберите действие + - : • : ")

if ded == '+' :
  c = rer + qwe
  print ("Ваш ответ: " + str(c) )
  
elif ded == '-' :
  c = rer - qwe
  print ("Ваш ответ: " + str(c) )
  
elif ded == '•':
   c = rer * qwe
   print ("Ваш ответ: " + str(c) )
  
elif ded == ':':
    c = rer / qwe
    print ("Ваш ответ: " + str(c) )

else:
  print("Введите корректное число")
