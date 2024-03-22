![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Laboratorio | Ronda de análisis de clientes 4

En la lección de hoy hablamos sobre distribuciones continuas (principalmente distribución normal), regresión lineal y cómo la multicolinealidad puede afectar el modelo. En esta práctica de laboratorio, pondremos a prueba sus conocimientos sobre esos aspectos utilizando el archivo `marketing_customer_analysis.csv`. Has estado usando los mismos datos en las prácticas de laboratorio anteriores (rondas 2 y 3). Puede continuar usando el mismo archivo jupyter. El archivo se puede encontrar en la carpeta `files_for_lab`.

### Obtener los datos

Utilice el archivo jupyter del último laboratorio (Ronda 3 de análisis de clientes)

### Completa la siguiente tarea

- Verificar los tipos de datos de las columnas. Obtenga los datos numéricos en un marco de datos llamado "numérico" y columnas categóricas en un marco de datos llamado "categóricos".
(Puede utilizar np.number y np.object para seleccionar los tipos de datos numéricos y los tipos de datos categóricos respectivamente)
- Ahora intentaremos comprobar visualmente la normalidad de las variables numéricas.
  - Utilice la biblioteca Seaborn para construir diagramas de distribución para las variables numéricas.
  - Utilice Matplotlib para construir histogramas.
  - ¿Las distribuciones para diferentes variables numéricas se parecen a una distribución normal?
- Para las variables numéricas, verifique la multicolinealidad entre las características. Tenga en cuenta que utilizaremos la columna `total_claim_amount` más adelante como variable de destino.
- Elimina una de las dos características que muestran una alta correlación entre ellas (superior a 0,9). Escriba código tanto para la matriz de correlación como para el mapa de calor marino. Si no hay un par de características que tengan una correlación alta, no descarte ninguna característica.