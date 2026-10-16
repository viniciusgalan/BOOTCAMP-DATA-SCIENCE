# BOOTCAMP-DATA-SCIENCE
numero = 15
es_fin_de_semana = True
esta_lloviendo = False  # <-- Esta linha evita o NameError

# 2. Testar o operador AND (faixa numérica)
if numero >= 10 and numero <= 20:
    print("El número está en el rango permitido (con and)")

if 10 <= numero <= 20:
    print("El número está en el rango permitido (forma compacta)")

# 3. Testar o operador OR
if es_fin_de_semana:
    print("¡Día de descanso!")

# 4. Testar o operador NOT
if not esta_lloviendo:
    print("Puedes salir a dar un paseo sin paraguas.")
else:
    print("Lleva paraguas.")  
