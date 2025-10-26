# Conector de datos: M.2 (NVMe/SATA)

**Descripción breve:** Ranura de expansión interna (formato M.2) que permite conectar unidades de almacenamiento SSD tanto con interfaz SATA como NVMe (PCIe). Se usa en placas base modernas de ordenadores y portátiles, proporcionando altas velocidades de transferencia y gran versatilidad   
**Pines/Carriles/Voltajes/Velocidad:**Conectores de 67 o 75 pines según key · 3.3V (típico) · SATA hasta 6 Gbps · NVMe (PCIe) hasta 32 Gbps (PCIe 3.0 x4) o más en generaciones superiores
**Uso principal:** Conexión de discos SSD de alta velocidad, tanto SATA (opción económica/retrocompatible) como NVMe (rendimiento máximo).
**Compatibilidad actual:** Alta

## Identificación física
- Conector plano y pequeño de contactos dorados, con una muesca (key) que puede estar en el borde B, M o ambos (B+M).

Los módulos suelen indicar en la etiqueta “NVMe” o “SATA”, y la ranura de la placa base suele estar identificada con “M.2”.

## Notas técnicas
- La key determina compatibilidad:

Key B: SATA o PCIe x2

Key M: PCIe x4 (para NVMe)

Key B+M: compatible en ambos tipos de ranuras (solo a velocidad del tipo más bajo)

Para aprovechar el máximo rendimiento de NVMe, es necesaria la Key M y que la placa sea compatible PCIe 3.0/4.0 o superior.

El M.2 no tiene alimentación propia —toma energía del bus principal de la placa madre (generalmente 3.3V); no requiere cables de alimentación externos

## Fotos
![M.2 (NVMe/SATA)](../../../assets/img/11-conectores_datos/M.2_NVMe_SATA.jpeg "M.2 (NVMe/SATA)")

## Fuentes
- https://pinoutguide.com/HD/M.2_NGFF_connector_pinout.shtml

- https://en.wikipedia.org/wiki/M.2

-https://www.kingston.com/en/ssd/what-is-nvme-ssd-technology