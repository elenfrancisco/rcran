
x <- "Hola"
y <- "UNTRM"
paste(x,y, sep = "-")

area_cir <- function(radio){
  pi*radio*radio
}

area_cir(radio = 10)
area_cir(radio = 15)
#crear funcion para el indice de masa corporal
imc <- function(weight, hight){weight/(hight*hight)}
imc(weight = 63, hight = 1.63)
# Datos de ejemplo: una lista de valores de IMC
imc <- c(17, 22, 27, 32, 37, 42)

# Asignar etiquetas según los valores de IMC
etiquetas_imc <- cut(imc,
                     breaks = c(-Inf, 18.5, 24.9, 29.9, 34.9, 39.9, Inf),
                     labels = c("Bajo peso", "Peso normal", "Sobrepeso", 
                                "Obesidad grado 1", "Obesidad grado 2", "Obesidad grado 3"))

# Mostrar los resultados
data.frame(IMC = imc, Categoria = etiquetas_imc)

