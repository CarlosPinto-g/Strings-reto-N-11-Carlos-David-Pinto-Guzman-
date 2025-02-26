# Strings-reto-N-11-Carlos-David-Pinto-Guzman-

# strings

### 1. Consulte que hacen los siguientes métodos de strings en python: endswith, startswith, isalpha, isalnum, isdigit, isspace, istitle, islower, isupper.

## *Endswith:* Este método verifica si una cadena termina con un cierto sufijo (suffix).Devuelve True si la cadena termina con ese sufijo y False si no.
## Ejemplo: 
```pseudocode
texto = "Hola, ¿cómo estás?"
print(texto.endswith("estás?"))  # True
print(texto.endswith("Hola"))    # False 
```



## *Startwith:* Este método verifica si una cadena comienza con un cierto prefijo (prefix). Devuelve True si la cadena empieza con ese prefijo y False si no. 
## Ejemolo:
```pseudocode
texto = "Python es increíble"
print(texto.startswith("Python"))  # True
print(texto.startswith("es"))      # False 
```



## *isalpha:* Este método verifica si la cadena contiene solo letras (sin espacios, números ni caracteres especiales). Si la cadena tiene al menos un carácter y solo contiene letras, devuelve True.
## Ejemplo: 
```pseudocode
print("HolaMundo".isalpha())  # True
print("Hola Mundo".isalpha())  # False (porque tiene un espacio)
print("Python3".isalpha())  # False (porque tiene un número) 
```



## *isalnum:* Este método verifica si la cadena contiene solo letras y/o números (sin espacios ni caracteres especiales). Si la cadena tiene al menos un carácter y solo contiene letras y números, devuelve True.
## Ejemplo: 
```pseudocode
 print("Python123".isalnum())  # True
print("Python 123".isalnum())  # False (porque tiene un espacio)
print("Hola_Mundo".isalnum())  # False (porque tiene un guion bajo)
```



## *isdigit:* Este método verifica si la cadena contiene solo números (dígitos del 0 al 9). Si la cadena tiene al menos un carácter y solo contiene números, devuelve True.
## Ejemplo: 
```pseudocode
 print("12345".isdigit())  # True
print("123.45".isdigit())  # False (porque tiene un punto decimal)
print("3a2".isdigit())  # False (porque tiene una letra)
```



## *isspace:* Este método verifica si la cadena contiene solo espacios en blanco. Si la cadena tiene al menos un carácter y solo contiene espacios, devuelve True.
## Ejemplo: 
```pseudocode
 print("   ".isspace())  # True
print("\t\n".isspace())  # True (tabulaciones y saltos de línea también cuentan como espacio)
print(" hola ".isspace())  # False (porque tiene letras)
```



## *istitle:* verifica si la cadena está en formato de título (cada palabra empieza con mayúscula y las demás letras son minúsculas). Si la cadena sigue este formato, devuelve True
## Ejemplo: 
```pseudocode
print("Hola Mundo".istitle())  # True
print("Hola mundo".istitle())  # False (porque 'mundo' no empieza en mayúscula)
print("PYTHON Es Genial".istitle())  # False (porque 'PYTHON' está todo en mayúscula) 
```



## *islower:* si la cadena está completamente en minúsculas. Si la cadena tiene al menos un carácter y todas sus letras están en minúsculas, devuelve True.
## Ejmplo: 
```pseudocode
 print("hola mundo".islower())  # True
print("Hola Mundo".islower())  # False (porque hay mayúsculas)
print("python3".islower())  # True (los números no afectan el resultado)
```



## *isupper:* Este método verifica si la cadena está completamente en mayúsculas. Si la cadena tiene al menos un carácter y todas sus letras están en mayúsculas, devuelve True.
## Ejemplo: 
```pseudocode
 print("HOLA MUNDO".isupper())  # True
print("Hola MUNDO".isupper())  # False (porque hay una palabra con minúsculas)
print("PYTHON3".isupper())  # True (los números no afectan el resultado)
```



##Resumen:
```pseudocode
Método          ¿Qué verifica?
             
endswith()	     Si la cadena termina con un sufijo
startswith()	   Si la cadena comienza con un prefijo
isalpha()	       Si solo contiene letras (sin espacios ni números)
isalnum()	       Si solo contiene letras y números (sin espacios ni símbolos)
isdigit()	       Si solo contiene números (dígitos)
isspace()	       Si solo contiene espacios en blanco
istitle()      	 Si cada palabra empieza en mayúscula y lo demás está en minúscula
islower()	       Si todas las letras están en minúscula
isupper()	       Si todas las letras están en mayúscula
```


