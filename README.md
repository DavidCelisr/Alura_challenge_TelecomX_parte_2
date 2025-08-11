# 📊 Análisis de Evasión de Clientes en TelecomX

## 📌 Descripción
Este proyecto tiene como objetivo identificar los principales factores que influyen en la cancelación de clientes y proponer estrategias de retención basadas en datos.  
Se trabajó con un conjunto de datos que incluye información de clientes, tipo de contrato, uso de servicios y gastos, entre otras variables.

## 🛠 Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## 🔍 Metodología
1. **Exploración y limpieza de datos**  
   - Eliminación de valores nulos y duplicados.
   - Conversión de variables categóricas a formato numérico.
   
2. **Análisis exploratorio**  
   - Visualización de patrones entre variables como:
     - Tiempo de contrato × Cancelación.
     - Gasto total × Cancelación.
   - Gráficos utilizados: boxplots, scatter plots y histogramas.

3. **Modelado predictivo**  
   - Se entrenaron varios modelos de Machine Learning, incluyendo:
     - Regresión logística.
     - Random Forest.
   - Se comparó el rendimiento de cada modelo utilizando métricas como accuracy, recall y precisión.

4. **Selección del modelo final**  
   - El modelo **Random Forest** obtuvo el mejor rendimiento.
   - Se utilizó para calcular la importancia de cada variable.

## 📊 Principales hallazgos
- **Tiempo de contrato** y **gasto total** fueron variables clave en la predicción de cancelación.
- Clientes con contratos mensuales y gastos más altos presentaron mayor probabilidad de cancelar el servicio.
- Otros factores relevantes incluyeron el tipo de servicio de internet y la existencia de cargos adicionales.

## 💡 Estrategias de retención sugeridas
- **Ofertas de fidelización** para clientes con contratos cortos.
- **Paquetes personalizados** que reduzcan los costos para usuarios con gastos elevados.
- **Programas de seguimiento** para clientes con quejas recurrentes o baja satisfacción.

🙋 Sobre mí
Mi nombre es David Celis, soy estudiante de Ciencias de Datos con interés en análisis de negocios, visualización de datos y automatización. Me apasiona transformar datos en decisiones.

Este proyecto fue desarrollado como parte de mi formación práctica y está orientado a resolver problemas reales mediante el análisis exploratorio de datos.

📫 Puedes contactarme a través de LinkedIn o por correo si deseas saber más sobre mi trabajo.

🙏 Agradecimientos
Gracias por tomarte el tiempo de revisar este proyecto.

Este análisis fue realizado como parte de una actividad formativa para aplicar técnicas de análisis exploratorio de datos, visualización y toma de decisiones basadas en evidencia, gracias al apoyo y el programa Oracle One con Alura.

¡Espero que te resulte útil o inspirador para tus propios proyectos!
