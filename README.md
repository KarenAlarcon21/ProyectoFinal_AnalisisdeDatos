# 📊 Análisis de Habitantes de Calle en Bogotá D.C. — Proyecto Final

Este repositorio contiene el análisis completo de los factores individuales y sociodemográficos que influyen en que una persona llegue a la situación de calle en Bogotá D.C., basado en datos abiertos de la ciudad.  
El proyecto se desarrolló en el marco del **Bootcamp de Análisis de Datos**, aplicando técnicas de limpieza, exploración y visualización de datos.

---

## 👥 Integrantes

- Leyder Andres Oyuela Vera  
- Karen Daniela Alarcón Ortiz  
- Carlos Felipe Rodríguez Conde  
- Johanna Aguirre Latorre  

**Instructor:** Ing. Victor Hugo Moncayo  
**Fecha:** Noviembre 2025  
**Lugar:** Bogotá D.C.

---

## 📌 Índice

- [Definición del problema](#Definición-del-problema)  
- [Información adicional](#Información-adicional)  
- [Objetivo General](Objetivo-general)  
- [Objetivos Específicos](#Objetivos-específicos)  
- [Análisis de datos](#Análisis-de-datos)  
  - [Clasificación inicial de variables](#Clasificación-inicial-de-variables)  
  - [Caracterización sociodemográfica](#Caracterización-sociodemográfica)  
  - [Factores asociados a la permanencia en calle](#Factores-asociados-a-la-permanencia-en-calle)  
- [Conclusiones](#Conclusiones)  
- [Posibles soluciones o mejoras](#Posibles-soluciones-o-mejoras)

---

## 🧩 Definición del problema

La población en situación de calle está compuesta por personas que carecen de una vivienda estable y adecuada. Este grupo presenta altos niveles de vulnerabilidad social debido a factores como pobreza extrema, rupturas familiares, falta de acceso a servicios básicos, consumo de sustancias psicoactivas y problemáticas de salud mental.

El objetivo principal del análisis es responder:

👉 **¿Cuáles son los factores individuales y sociodemográficos que influyen en que las personas lleguen a la situación de calle?**

---

## 📚 Información adicional

Algunos puntos relevantes del contexto normativo e institucional:

- **Ley 1641 de 2013**: Establece mecanismos para garantizar los derechos de las personas habitantes de calle.
- **Secretaría Distrital de Integración Social**: Ofrece servicios de atención sociosanitaria.
- **DANE**: Responsable de la caracterización demográfica y socioeconómica.
- **DNP**: Incluye a esta población en los sistemas de focalización social (SISBEN).
- **ICBF**: Atiende a niños, niñas y adolescentes en condición de vulnerabilidad.

Además, entre 2013 y 2016 se llevaron a cabo ejercicios técnicos y foros para avanzar en la formulación de políticas públicas dirigidas a esta población.

---

## 🎯 Objetivo General

**Determinar los factores individuales y sociodemográficos que llevan a las personas a la situación de calle.**

---

## 🎯 Objetivos Específicos

1. Caracterizar sociodemográfica e individualmente a la población habitante de calle.
2. Analizar los factores que pudieron llevar a las personas a su situación actual.
3. Presentar y visualizar los resultados derivados del análisis de datos.

---

## 📈 Análisis de datos

Para este proyecto se utilizó una base de datos de **Datos Abiertos Bogotá (2024)** con:

- **10.470 filas**
- **123 columnas**
- Datos completamente anonimizados

Después del filtrado y limpieza, la muestra para análisis quedó en **7.117 registros**.

---

### 📂 Clasificación inicial de variables

Se seleccionaron variables agrupadas en:

#### **🔹 Factores individuales**
- Consumo de SPA (P30_1)  
- Edad de inicio de consumo (P30S9A1)  
- Nivel educativo (P16)  
- Razones para llegar a la calle (P20)  
- Razones para permanecer en calle (P21)  
- Sexo (P10)  
- Edad (P12)  
- Vinculación laboral previa (P40)  

#### **🔹 Factores sociodemográficos**
- Lugar de origen (P11)  
- Grupo étnico (P13)  
- Localidad donde duerme habitualmente (P7S1A)  

---

## 🗺️ Caracterización sociodemográfica

Algunos hallazgos destacados:

- **Localidades con mayor concentración:** Los Mártires (14.33%), Santa Fe (13.73%), Kennedy (9.78%).  
- **Sexo:** Predomina el sexo masculino (91.22%).  
- **Grupo étnico:** Mayoría no pertenecen a ningún grupo étnico (6.867 personas).  
- **Lugar de nacimiento:** Más del 60% son nacidos en Bogotá (4.500 personas).  

---

## 🔍 Factores asociados a la permanencia en calle

Se analizaron variables de contexto y trayectoria de vida:

### 🔸 Principales razones para llegar a la calle
- Conflictos familiares o violencia → **2.755 personas**
- Consumo de sustancias psicoactivas → **2.238 personas**

Estas dos razones representan **el 70.15%** del total analizado.

### 🔸 Inicio del consumo de sustancias
- Se concentra entre los **10 y 17 años**, con un pico entre **13 y 15 años**.
- Disminuye considerablemente después de los 20 años.

### 🔸 Consumo por edad
- La cantidad total de sustancias consumidas disminuye conforme avanza la edad.
- Los grupos más afectados están entre los **33 y 50 años**.

### 🔸 Escolaridad
- Predominan niveles educativos: primaria, secundaria y media.
- Los hombres representan la mayor parte de los registros.

### 🔸 Vinculación laboral previa
- La mayoría de hombres tuvieron algún tipo de vinculación laboral antes de llegar a la calle.
- En las mujeres predominan los casos sin vinculación laboral.

---

## 📝 Conclusiones

- La situación de calle **no es causada por un solo factor**, sino por la acumulación de variables individuales, familiares y estructurales.
- El consumo temprano de SPA, los conflictos familiares y la falta de apoyo emocional son detonantes frecuentes.
- La mayoría de habitantes de calle son **hombres nacidos en Bogotá**, con niveles educativos bajos y trayectorias laborales interrumpidas.
- Aunque existen políticas públicas, su alcance real y efectividad requieren una evaluación más profunda.

---

## 🔧 Posibles soluciones o mejoras

1. **Mayor acceso a salud mental y apoyo emocional.**  
2. **Programas de tratamiento para consumo flexibles y humanizados.**  
3. **Estrategias de recuperación y fortalecimiento de redes familiares.**  
4. **Formación laboral práctica y acompañada.**  
5. **Centros de acogida fortalecidos y con enfoque territorial.**

---

