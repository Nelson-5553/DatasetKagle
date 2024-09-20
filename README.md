## DatasetKaggle

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Counter_Strike_2_Logo.png/800px-Counter_Strike_2_Logo.png?20230322172524" alt="Texto alternativo" width="100%"/>
</div>

# Sobre este Dataset

El conjunto de datos consta de datos ronda por ronda, el conjunto de datos totaliza 74929 rondas de partidos de deportes electrónicos de CS:GO. Cada ronda incluye información sobre el mapa, número de ronda, número de rondas ganadas CT y T, el nombre de los equipos de cada lado, el lado ganador y perdedor y el equipo, tipo de compra y costo.

Este conjunto de datos se obtuvo extrayendo datos de hltv.org Datos que a suvez fueron compartidos por el usuario [Livanof en Kaggle](https://www.kaggle.com/datasets/livanoff/csgo-esport-matches-round-data/data).

# Columnas

Cada ronda incluye información sobre el mapa, número de ronda, número de rondas ganadas CT y T, el nombre de los equipos de cada lado, el lado ganador y perdedor y el equipo, tipo de compra y costo.

### Descripción de las columnas del dataset

1. **Unnamed: 0**: 
   - Índice generado automáticamente. Puede ser un identificador innecesario, agregado por defecto al cargar el archivo.

2. **mapName**: 
   - El nombre del mapa donde se jugó la ronda (por ejemplo: "Dust II", "Inferno", "Mirage").

3. **roundNum**: 
   - El número de la ronda en el partido. Indica qué ronda fue en el transcurso del encuentro.

4. **tScore**: 
   - Puntaje del equipo **Terrorista (T)** al inicio de la ronda (es decir, cuántas rondas había ganado el equipo T antes de comenzar esta ronda).

5. **ctScore**: 
   - Puntaje del equipo **Counter-Terrorista (CT)** al inicio de la ronda (es decir, cuántas rondas había ganado el equipo CT antes de comenzar esta ronda).

6. **endTScore**: 
   - Puntaje del equipo **Terrorista (T)** al final de la ronda. Muestra cuántas rondas ganó el equipo T al concluir la ronda.

7. **endCTScore**: 
   - Puntaje del equipo **Counter-Terrorista (CT)** al final de la ronda. Muestra cuántas rondas ganó el equipo CT al concluir la ronda.

8. **ctTeam**: 
   - El nombre del equipo que jugaba como **Counter-Terrorista (CT)** en esa ronda.

9. **tTeam**: 
   - El nombre del equipo que jugaba como **Terrorista (T)** en esa ronda.

10. **roundEndReason**: 
    - La razón por la cual la ronda terminó. En CS:GO, las rondas pueden concluir de diferentes maneras, como:
      - Eliminación de todos los jugadores de un equipo.
      - Plantación o desactivación de la bomba.
      - Fin del tiempo.

11. **ctRoundStartEqVal**: 
    - El valor económico total del equipo **Counter-Terrorista (CT)** al inicio de la ronda (incluye armas, equipo, etc.).

12. **ctRoundSpendMoney**: 
    - Cantidad de dinero que el equipo **Counter-Terrorista (CT)** gastó antes de comenzar la ronda.

13. **ctBuyType**: 
    - Tipo de compra que realizó el equipo **Counter-Terrorista (CT)**, como:
      - **Full-buy**: Compra completa de armas y equipo.
      - **Eco**: Ronda con ahorro de dinero.
      - **Force-buy**: Compra forzada con dinero limitado.

14. **tFreezeTimeEndEqVal**: 
    - Valor económico total del equipo **Terrorista (T)** al final del tiempo de congelación (inicio de la ronda).

15. **tRoundStartEqVal**: 
    - El valor económico total del equipo **Terrorista (T)** al inicio de la ronda (incluye armas, equipo, etc.).

16. **tRoundSpendMoney**: 
    - Cantidad de dinero que el equipo **Terrorista (T)** gastó antes de comenzar la ronda.

17. **tBuyType**: 
    - Tipo de compra que realizó el equipo **Terrorista (T)**, similar a `ctBuyType`.

18. **winningSide**: 
    - El lado que ganó la ronda: **Terrorista (T)** o **Counter-Terrorista (CT)**.

19. **winningTeam**: 
    - El equipo que ganó la ronda.

20. **losingTeam**: 
    - El equipo que perdió la ronda.

# Analisis EDA







