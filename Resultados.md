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

ㅤㅤ

Aquí adjunto los resultados del test de rendimiento:
