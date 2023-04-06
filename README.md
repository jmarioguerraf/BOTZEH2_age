# BOTZEH2_age
It's a small Python code that I aks about the age and return some possibilities.
import time

def start():
    
print ("Digite sua idade:")
idade = int(input ( ))
time.sleep (1)
print (idade,("?"))
time.sleep (0.5)
if idade < 18 :
    print ("Você é uma criança. Solte o celular e vá brincar!")
elif idade in range(18, 59) :
    print ("Tudo bem. Seja bem-vindo!")
elif idade in range(60, 100000000000) :
    print ("Tudo bem. Você é adulto, mas não demore muito para dormir.")
else :
    print ("Informação Inválida")
time.sleep (0.5)

print ("Avaliação Concluída")
    
While:
    start()

# COULD YOU HELP ME TO CREATE A LOOPING, THAT IT COME UP TO def start() ?
