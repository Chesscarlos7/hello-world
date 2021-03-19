# hello-world

# Funciones-para-calculadoras.
# Funciones parser(), expr(), compile() y eval().
# Permite tratar una expresión matemática en string.
# Es la expresión clave que realiza el cáculo.

def resultado():  #haciendo click en igual de la calculadora.
    global expresion #variable global que permite ser llamada desde cualquier punto del programa.
    try:
        resultado=str(eval(expresion)) #Intenta llevar a cabo la solución de la expresión matemática, la cual se encuentra como string.
        a_pantalla.set(resultado) #Coloca el resultado en la pantalla de la calculadora.
    except:
        a_pantalla.set("ERROR")  #En casos de división por cero o cualquier otro posible error de cómputo.
    expresion = ""
    
#EJEMPLO    

resultado=0
resultado=str(eval(2+5*10-12+2**3

print(resultado)
