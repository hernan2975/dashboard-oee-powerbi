# 📈 Dashboard OEE (Overall Equipment Effectiveness)

Dashboard funcional en Power BI para monitoreo de eficiencia operativa en entornos industriales (maquinaria, taller, planta).

## 📊 Métricas incluidas
- **Disponibilidad** = Tiempo Operativo / Tiempo Planificado  
- **Rendimiento** = (Producción / Tiempo Operativo) / Velocidad Estándar  
- **Calidad** = Producción Buena / Producción Total  
- **OEE** = Disponibilidad × Rendimiento × Calidad

## 📁 Contenido
- `oee_data_sample.csv`: dataset de ejemplo (editable en Excel)
- `OEE_Analysis.pbix`: archivo Power BI listo para abrir y modificar
- `docs/modelo_relacional.drawio.png`: diagrama del modelo estrella (dimensiones: tiempo, máquina, turno)

## ▶️ Cómo usar
1. Abrir `OEE_Analysis.pbix` con Power BI Desktop (gratis).
2. Editar fuente de datos si usás tu propio CSV.
3. Publicar en Power BI Service (opcional) o usar en modo local.
