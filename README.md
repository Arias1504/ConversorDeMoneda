# 💱 Conversor de Monedas

## Descripción del Proyecto
Este es un proyecto de consola para convertir monedas entre diferentes divisas utilizando la API de ExchangeRate-API. Permite a los usuarios convertir entre dólares, pesos argentinos, reales brasileños y pesos colombianos de manera sencilla.

## 🌟 Características
- Conversión entre múltiples monedas
- Interfaz de consola intuitiva
- Conexión en tiempo real con API de tasas de cambio
- Manejo de errores y validación de entrada

## 🛠️ Tecnologías Utilizadas
- Java
- Gson (para manejo de JSON)
- HttpClient (para solicitudes HTTP)
- [ExchangeRate-API](https://www.exchangerate-api.com/)

## 📋 Requisitos Previos
- JDK 11 o superior
- Conexión a Internet
- Biblioteca Gson

## 🚀 Instalación

### Clonar el Repositorio
```bash
git clone https://github.com/[TU_USUARIO]/ConversorDeMoneda.git
```
```bash
cd ConversorDeMoneda 
```

## 📦 Dependencias
- Gson 2.11.0 ([gson-2.11.0.jar](https://mvnrepository.com/artifact/com.google.code.gson/gson/2.11.0))

### Instalación Manual
1. Descarga el archivo `gson-2.11.0.jar`
2. Agrega el JAR a tu proyecto:
   - En Eclipse: Haz clic derecho en tu proyecto > Build Path > Configure Build Path > Libraries > Add External JARs
   - En IntelliJ IDEA: File > Project Structure > Modules > Dependencies > Add > JARs or directories

## 🎮 Uso
1. Ejecuta la aplicación
2. Selecciona la opción de conversión deseada
4. Ingresa la cantidad a convertir
5. Visualiza el resultado de la conversión

## 💡 Funcionalidades
- Conversión de USD a ARS
- Conversión de ARS a USD
- Conversión de USD a BRL
- Conversión de BRL a USD
- Conversión de USD a COP
- Conversión de COP a USD

## 🔒 Configuración de API
Utiliza tu propia API key de [ExchangeRate-API](https://www.exchangerate-api.com/)
Reemplaza `YOUR-API-KEY` en la clase `ConsultaModena` con tu clave personal.

## Autor
Proyecto desarrollado por [Arias1504](https://github.com/Arias1504).
