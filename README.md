# Juego de Naves

Simulador de Combate Espacial en Consola desarrollado en C++ aplicando
Programacion Orientada a Objetos (POO): clases `Nave`, `Asteroide` y `Bala`.

## Materia
Laboratorio de Programacion (LPR) - 5 Ano - E.E.S.T. N 1 "Eduardo Ader", Vicente Lopez.

## Controles
- `W`, `A`, `S`, `D`: mover la nave
- `ESPACIO`: disparar

## Estructura
```
juegodenaves/
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
├── docs/
│   ├── InformeEEST1_LPR2026_ACT08_G03_v1.0.0.pdf
│   ├── CHANGELOG.md
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf
│       └── manual_usuario_v1.0.0.pdf
├── src/
│   └── main.cpp
└── capturas/
    └── combate_consola.png
```

## Compilacion
```bash
g++ src/main.cpp -o juegodenaves.exe
```
Requiere Windows (usa `windows.h` y `conio.h`).
