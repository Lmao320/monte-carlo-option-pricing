# Monte Carlo Option Pricing

Valoración de **opciones europeas (Call y Put)** con simulación **Monte Carlo** y comparación con la fórmula analítica de **Black-Scholes**.

## Qué hace

- Simula 1.000 trayectorias de precio con **movimiento browniano geométrico**.
- Calcula el precio de Call y Put por Monte Carlo y por Black-Scholes.
- Muestra la diferencia entre ambos métodos.
- Animación de 20 trayectorias de precio.

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
python Main.py
```

## Limitaciones

- Parámetros fijos (S0 = 100, K = 100, σ = 20%, r = 5%, T = 1 año).
- Volatilidad constante y solo opciones europeas.

## Autor

**Santiago Peña Díaz** — Estudiante de Ingeniería de Sistemas (CUN, Colombia)

- GitHub: [Lmao320x](https://github.com/Lmao320x)
- Documentación completa: [Portafolio en Notion](https://freezing-hope-5b5.notion.site/Portafolio-de-Proyectos-Santiago-Pe-a-D-az-41f7f18e4ca2811793dcece91c3d00c0)
