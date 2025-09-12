# Lunar Lander

Et simpelt C-program, der simulerer styring af en rumlander's thruster baseret på højde. Diagrammet i **LunarLander.drawio** viser logikken.

## Brug
```bash
gcc LunarLander.c -o LunarLander
./LunarLander
```

Programmet tester forskellige højder og udskrive om thruster-adfærden er korekt:
- Over 100 --> thruster = 0
- 1-100 --> thruster = 1
- 0 eller lavere --> thruster = 0

Filer:
- LunarLander.c - Program
- LunarLander.drawio - Diagram
