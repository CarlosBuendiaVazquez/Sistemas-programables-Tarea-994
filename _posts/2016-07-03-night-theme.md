---
# Actuadores

---

## ¿Qué son los actuadores?
- Dispositivos que convierten energía en movimiento físico.
- Usados en automatización, robótica y control industrial.
- Tipos de movimiento: lineal o rotativo.

---

## Actuadores Eléctricos
### ¿Qué es?
- Convierte energía eléctrica en movimiento mecánico.
### Tipos
- **Motores DC/AC**: Corriente continua o alterna.
- **Actuadores lineales**: Movimiento lineal.
- **Servomotores**: Control preciso.
### Características
- Precisión, eficiencia y bajo mantenimiento.
### Funcionamiento
- Señales eléctricas -> movimiento.
### Comunicación
- PWM, digital, protocolos industriales.

---

## Actuadores Mecánicos
### ¿Qué es?
- Convierte energía manual o motorizada en movimiento mecánico.
### Tipos
- Tornillo sin fin, cremallera y piñón, poleas.
### Características
- Robustez, durabilidad y fuerza.
### Funcionamiento
- Mecanismos de engranajes y poleas.
### Comunicación
- Manual o sistemas de control mecánico.

---

## Actuadores Hidráulicos
### ¿Qué es?
- Convierte presión de fluido en movimiento.
### Tipos
- Cilindros, motores y bombas hidráulicas.
### Características
- Alta fuerza, control de presión.
### Funcionamiento
- Presión en fluido -> movimiento de pistón.
### Comunicación
- Válvulas, sensores y control remoto.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
