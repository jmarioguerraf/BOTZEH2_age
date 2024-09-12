#BOTZEH2_age
It's a small Python code that I aks about the age and return some possibilities.

#START

    import time
    
    while True:
    print ("Digite sua idade ('sair' para terminar):")
    entrada = input()
    
    if entrada.lower() == 'sair':
        print("Programa encerrado.")
        break
    
    try:
        idade = int(entrada)
    except ValueError:
        print("Por favor, digite um número válido.")
        continue
    
    print (idade,("?"))

    if idade < 18 :
        print ("Você é uma criança. Solte o celular e vá brincar!")
        time.sleep (2)
        print ("AGORA!!!")
    
    elif idade in range(18, 59) :
        print ("Tudo bem. Seja bem-vindo!")
        time.sleep(1)
        print ("Aliás... Que tal olhar em sua volta e ver se tem alguma criança precisando brincar?")
    
    elif idade in range(60, 130) :
        print ("Tudo bem. Você é adulto, mas não demore muito para dormir.")
    
    elif idade in range (131, 9999) :
        print ("Informação inválida!!!")
    
    time.sleep (1)

    print ("Avaliação concluída.")
    time.sleep(1)


#COULD YOU HELP ME WITH SOME IMPROVEMENT?

#THAT'S A NEW PART OF THE TEXT, ABOUT MY GITHUB CLASSES.
