# Inicializar las variables
h = 0 # Número de monedas de h
p = 2 * h # Número de monedas de p
l = p + 10 # Número de monedas de l

# Repetir hasta que la suma sea 85
while h + p + l == 85:

# Incrementar h en 1
h = h + 1

# Actualizar los valores de p y l
p = 2 * h
l = p + 10

# Imprimir los resultados
print(h)
print(p)
print(l)
