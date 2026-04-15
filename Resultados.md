# Identificación del Procesador en el Sistema

Aquí tenemos los datos que nos proporciona el sistema tanto en Windows como en Linux:

<img width="886" height="642" alt="image" src="https://github.com/user-attachments/assets/61a5195c-75eb-42a0-8856-0a2857d2cae0" />
ㅤㅤ
ㅤㅤ

ㅤ

ㅤ
<img width="886" height="498" alt="image" src="https://github.com/user-attachments/assets/0d35aade-a6e8-4de4-b5ab-a0a558c6215a" />

ㅤ
ㅤ

<img width="886" height="552" alt="image" src="https://github.com/user-attachments/assets/d5e565d8-3a66-4172-acd1-c890c330dc00" />

ㅤ

<img width="886" height="557" alt="image" src="https://github.com/user-attachments/assets/96214fd4-9049-4ea2-9b14-c1790f786796" />
<img width="886" height="556" alt="image" src="https://github.com/user-attachments/assets/70297e41-4bbb-4a6d-ae71-336afa0d26cb" />


### Estos son los datos estructurados:


| Característica | Detalle |
| :--- | :--- |
| **Modelo exacto** | Intel(R) Core(TM) i3-4160 CPU |
| **Velocidad base** | 3,60 GHz |
| **Número de núcleos** | 2 (con 4 procesadores lógicos/hilos) |
| **Memoria caché L3** | 3,0 MB |

ㅤ

# Investigación en la Web del Fabricante

Esta es la web oficial de la verificación oficial para comparar los resultados co los nuestros: https://www.intel.la/content/www/xl/es/products/sku/77488/intel-core-i34160-processor-3m-cache-3-60-ghz/specifications.html


| Característica | Datos de tu Sistema | Datos Oficiales Intel ARK | ¿Coincide? |
| :--- | :--- | :--- | :--- |
| **Modelo** | Intel Core i3-4160 | Intel Core i3-4160 | Sí |
| **Velocidad Base** | 3,60 GHz | 3,60 GHz | Sí |
| **Frecuencia Boost** | No aplica | No tiene (N/A) | Sí |
| **Núcleos / Hilos** | 2 núcleos / 4 hilos | 2 núcleos / 4 hilos | Sí |
| **Caché L3 (Smart Cache)** | 3,0 MB | 3 MB | Sí |
| **Litografía (Tamaño)** | 22 nm | 22 nm | Sí |

ㅤㅤ

**Sobre la Frecuencia Boost**: El Intel i3-4160 no tiene tecnología "Intel Turbo Boost". Su frecuencia es fija a 3,60 GHz. Por eso, tanto en el Administrador de tareas como en HWiNFO64, la velocidad máxima siempre es la base.
ㅤㅤ

**Sobre la Caché L3**: El sistema reporta correctamente 3 MB de Intel® Smart Cache. Al ser un procesador de 4ª generación (Haswell) de gama de entrada, esta es la cantidad estándar diseñada por Intel. 

ㅤㅤ

# Benchmarking (Prueba de Rendimiento)

Aquí adjunto los resultados del test de rendimiento:

ㅤㅤ

<img width="628" height="628" alt="image" src="https://github.com/user-attachments/assets/347baa61-dca7-4009-9d5c-222947de3e0b" />

ㅤㅤ

<img width="886" height="826" alt="image" src="https://github.com/user-attachments/assets/dc68bee1-4b25-4e6e-b016-0ce1565dc6c5" />

ㅤㅤ

<img width="886" height="749" alt="image" src="https://github.com/user-attachments/assets/370d13a3-7b4e-4271-947f-9828f13e04ed" />

ㅤㅤ

**Mi puntuación en Multi-Thread es de 910.08. Al compararlo con procesadores similares en la base de datos de CPU-Z, el rendimiento es correcto para un i3-4160, por lo que se descarta cualquier estafa o modelo inferior camuflado.**

ㅤㅤ

# Informe de Análisis Crítico y Conclusión: Caso Intel Core i3-4160

Tras recoger y analizar los datos de mi equipo, estos son las conclusiones finales obtenidas:

* **Verificación en mi sistema:** He analizado mi procesador con tres fuentes distintas: el terminal de Linux (`lscpu`), **HWiNFO64** y **CPU-Z**. Las tres herramientas coinciden en que mi modelo es un **Intel Core i3-4160**.
* **Concordancia técnica:** Mi sistema reporta **3.0 MB de caché L3** y una velocidad base de **3.60 GHz**. Al consultar la hoja de especificaciones oficial en [Intel ARK](https://www.intel.la/content/www/xl/es/products/sku/77488/intel-core-i34160-processor-3m-cache-3-60-ghz/specifications.html), estos datos coinciden exactamente con el diseño de fábrica, lo que reduce drásticamente la posibilidad de un engaño por software.

* **Mi Benchmark:** He realizado el test de estrés con **CPU-Z (v17.01.64)**, obteniendo una puntuación de **910.8** en Multi-Thread.
* **Comparativa:** Según la base de datos de [CPU-Monkey](https://www.cpu-monkey.com/es/cpu-intel_core_i3_4160), un i3-4160 estándar debería marcar unos **974 puntos**. Mi resultado representa una diferencia de solo el **6.48%**.
* **Conclusión del rendimiento:** Al ser una diferencia menor al 10%, se confirma que mi procesador rinde como un i3-4160 auténtico. Si fuera un procesador inferior camuflado, la caída de rendimiento en el benchmark habría sido superior al 25%.

##  Acciones como consumidor si el procesador hubiera sido una estafa
Si tras realizar estas pruebas hubiera descubierto que mi procesador rinde un 25% menos de lo especificado por el fabricante, las acciones a tomar serían:

1.  **Exigir la garantía legal:** Presentar las capturas de pantalla de los benchmarks como prueba de que el producto no tiene las características publicitadas (publicidad engañosa).
2.  **Denuncia técnica:** Notificar al fabricante original (en este caso Intel) que se está distribuyendo hardware manipulado bajo su nombre.
3.  **Alerta comunitaria:** Compartir los resultados en plataformas de consumidores para evitar que otros usuarios caigan en la misma estafa.

---

### Materiales y Software Utilizados:

| Categoría | Herramientas / Fuentes |
| :--- | :--- |
| **Hardware verificado** | Intel Core i3-4160 @ 3.60GHz |
| **Software Windows** | CPU-Z v2.10 (Benchmark 17.01.64) y HWiNFO64 |
| **Software Linux** | Comandos `lscpu` y `cat /proc/cpuinfo` |
| **Fuentes Externas** | [Intel ARK (Spec Sheet)](https://www.intel.la/content/www/xl/es/products/sku/77488/intel-core-i34160-processor-3m-cache-3-60-ghz/specifications.html) y [CPU-Monkey](https://www.cpu-monkey.com/es/cpu-intel_core_i3_4160) |
