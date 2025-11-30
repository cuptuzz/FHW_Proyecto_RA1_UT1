# Parte 2 — Selección y comparación de componentes (único archivo)

> **Instrucciones generales**  
> 1) **Todo en este único archivo**.  
> 2) Las capturas guárdalas en `assets/img/20-parte2/` y enlázalas con ruta relativa.  
> 3) Cita **URL** de cada ficha y justifica la elección según **oficina** o **gaming**.  

---

## 1) Búsqueda de componentes (tienda online)
Elige una o varias tiendas (p. ej., **PcComponentes**, **Amazon ES**, **LDLC ES**). Completa las **4 fichas** siguientes.

### 1.1 Memoria RAM — PC de oficina
| Campo | Valor |
|---|---|
| **Marca y modelo** | Kingston FURY Beast |
| **Capacidad** | 16 GB (2x8GB) |
| **Velocidad / Timings** | 3200 MHz / CL16 |
| **Tipo (DDR4/DDR5) y formato (DIMM/SO-DIMM)** | DDR4 DIMM |
| **Precio (€)** | 42,99€ (Aprox. según oferta) |
| **URL** | [Ver en PcComponentes](https://www.pccomponentes.com/kingston-fury-beast-ddr4-3200-mhz-16gb-2x8gb-cl16) |
| **Captura** | ![ram_oficina](/retos/Reto_03_Elementos_Internos_SI/img/kingstonfurybeast.png|
| **Justificación** | Para un uso de oficina (navegación web, ofimática, gestión), 16 GB es el estándar actual para garantizar fluidez. La tecnología DDR4 es madura, muy estable y económica, ofreciendo la mejor relación coste-rendimiento para equipos que no requieren el ancho de banda extremo de DDR5. |

### 1.2 Memoria RAM — PC gaming
| Campo | Valor |
|---|---|
| **Marca y modelo** | Corsair Vengeance RGB (Optimizado AMD/Intel) |
| **Capacidad** | 32 GB (2x16GB) |
| **Velocidad / Timings / XMP-EXPO** | 6000 MHz / CL36 / AMD EXPO & Intel XMP |
| **Tipo (DDR4/DDR5)** | DDR5 |
| **Precio (€)** | 479,95€ |
| **URL** | [Ver en PcComponentes](https://www.pccomponentes.com/corsair-vengeance-rgb-ddr5-6000mhz-32-gb-2x16gb-cl36-memoria-dual-amd-expo-e-intel-xmp) |
| **Captura** | ![ram_gaming](/retos/Reto_03_Elementos_Internos_SI/img/corsairvengeanceDDR5.png) |
| **Justificación** | En un entorno gaming moderno, los 6000 MHz son el "punto dulce" para procesadores Ryzen 7000/9000. 32 GB aseguran que no haya cuello de botella en juegos exigentes actuales ni futuros, permitiendo multitarea (streaming, Discord) sin problemas. La latencia CL36 ofrece un buen equilibrio entre velocidad y precio. |

### 1.3 Microprocesador — PC de oficina
| Campo | Valor |
|---|---|
| **Marca y modelo** | Intel Core i3-12100 |
| **Núcleos / Hilos** | 4 Cores / 8 Hilos |
| **Frecuencias (base/boost)** | 3.3 GHz / 4.3 GHz |
| **Gráficos integrados** | Sí (Intel UHD Graphics 730) |
| **TDP / Consumo** | 60W (Base) / 89W (Turbo) |
| **Precio (€)** | 118,99€ |
| **Socket / Compatibilidad** | LGA 1700 |
| **URL** | [Ver en PcComponentes](https://www.pccomponentes.com/intel-core-i3-12100-33-ghz) |
| **Captura** | ![cpu_oficina](/retos/Reto_03_Elementos_Internos_SI/img/i3-12100.png) |
| **Justificación** | Este procesador es ideal para oficina por su alto rendimiento en mononúcleo, lo que agiliza la apertura de programas y navegación. Al incluir gráficos integrados, permite montar el equipo sin gastar en una tarjeta gráfica dedicada, reduciendo coste y consumo eléctrico. |

### 1.4 Microprocesador — PC gaming
| Campo | Valor |
|---|---|
| **Marca y modelo** | AMD Ryzen 7 7800X3D |
| **Núcleos / Hilos** | 8 Cores / 16 Hilos |
| **Frecuencias (base/boost)** | 4.2 GHz / 5.0 GHz |
| **Caché** | 96 MB L3 (Tecnología 3D V-Cache) |
| **TDP / Consumo** | 120W |
| **Precio (€)** | 358,67€ |
| **Socket / Compatibilidad** | AM5 |
| **URL** | [Ver en PcComponentes](https://www.pccomponentes.com/procesador-amd-ryzen-7-7800x3d-42ghz-5ghz-tray) |
| **Captura** | ![cpu_gaming](/retos/Reto_03_Elementos_Internos_SI/img/r77800x3d.png) |
| **Justificación** | Es considerado el mejor procesador para gaming puro gracias a su caché 3D apilada, que mejora drásticamente los fps y la estabilidad (1% lows) en juegos. Su eficiencia energética es superior a la competencia, permitiendo un alto rendimiento sin requerir sistemas de refrigeración extremos. |

> **Notas:** Precios consultados en PcComponentes en Noviembre 2025.

---

## 2) Tabla comparativa — Tipos de RAM encontrados
Compara **al menos DDR4 vs DDR5**. Si has encontrado más variaciones (p. ej. distintas velocidades), amplía filas.

| Tipo RAM | Velocidad típica (MT/s) | Voltaje típico | Consumo/eficiencia | Precio por GB (aprox.) | Compatibilidad con placas | Observaciones |
|---|---:|---:|---:|---:|---|---|
| DDR4 | 3200 MT/s | 1.2V - 1.35V | Estándar (Gestión en placa) | ~3,50€ / GB | Intel LGA 1700 (DDR4), AMD AM4 | Tecnología consolidada, muy económica y suficiente para uso general. |
| DDR5 | 5200 - 6400 MT/s | 1.1V - 1.25V | Mejorada (PMIC en módulo) | ~5,50€ / GB | Intel LGA 1700 (DDR5), AMD AM5 | Mayor ancho de banda, gestión de energía en el propio módulo. |

> Referencia rápida: documenta **placas base compatibles** y si tu CPU escogida admite el tipo de RAM. El i3-12100 admite ambas (según placa), el Ryzen 7 7800X3D solo DDR5.

---

## 3) Investigación — DDR5
Responde con apoyo de fuentes (cítalas al final de este archivo).

1. **Ventajas frente a DDR4:** DDR5 duplica el ancho de banda teórico y la densidad por módulo respecto a DDR4. Introduce el PMIC (Power Management Integrated Circuit) directamente en el módulo de memoria, lo que permite una regulación de voltaje más precisa y eficiente (1.1V base). También cuenta con dos subcanales de 32 bits por módulo para mejorar la eficiencia en el acceso concurrente y ECC (corrección de errores) *on-die* para mayor estabilidad a altas frecuencias.

2. **Usos donde se aprecia la diferencia:** Se nota especialmente en aplicaciones que dependen de un gran ancho de banda de memoria, como la compresión de archivos (7-Zip), edición de vídeo en alta resolución y renderizado 3D. En gaming, beneficia a títulos con mucha carga de CPU o mundos abiertos, mejorando los fps mínimos y reduciendo tirones.

3. **Ejemplo ventajoso:** Un equipo destinado a **streaming y edición de vídeo simultáneos** con un procesador de muchos núcleos (como un Ryzen 9). El mayor ancho de banda de DDR5 permite alimentar de datos a todos los núcleos del procesador de forma más eficiente que DDR4, reduciendo tiempos de espera y mejorando la fluidez del sistema bajo carga pesada.

---

## 4) Fuentes
- [PcComponentes] — [Intel Core i3-12100](https://www.pccomponentes.com/intel-core-i3-12100-33-ghz)
- [PcComponentes] — [Kingston FURY Beast DDR4](https://www.pccomponentes.com/kingston-fury-beast-ddr4-3200-mhz-16gb-2x8gb-cl16)
- [PcComponentes] — [AMD Ryzen 7 7800X3D](https://www.pccomponentes.com/procesador-amd-ryzen-7-7800x3d-42ghz-5ghz-tray)
- [PcComponentes] — [Corsair Vengeance DDR5](https://www.pccomponentes.com/corsair-vengeance-rgb-ddr5-6000mhz-32-gb-2x16gb-cl36-memoria-dual-amd-expo-e-intel-xmp)