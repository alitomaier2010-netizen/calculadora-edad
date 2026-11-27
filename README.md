# Calculadora de Edad (Python & C++)

**Actividad 1 — Revisión integral (Python & C++)** · Laboratorio de Programación · 5.º 3.ª A-B · E.E.S.T. N.º 1 «Eduardo Ader»

Programa que calcula la **edad exacta** de una persona restando su año de nacimiento al año actual
(fecha de referencia del ejercicio: **8/7/2026**) y descontando un año si todavía no cumplió años.
Antes de calcular aplica un *filtro de consistencia* que verifica que la fecha exista en el calendario
real (meses de 30/31 días y años bisiestos).

- Estudiante: **Alexis Maier**
- Lenguajes: C++ (`proyecto_cpp/`) y Python (`proyecto_python/`)

## Datos institucionales

- **Institución:** E.E.S.T. N.º 1 «Eduardo Ader» — Vicente López
- **Curso:** 5.º 3.ª A-B
- **Materia:** Laboratorio de Programación (LPR)
- **Profesor:** Prof. York
- **Actividad:** 1 — Revisión integral (Python y C++)

## Presentación de la Actividad

Calculadora de edad exacta con validación de fecha real (meses de 30/31 días y año bisiesto), resuelta primero en C++ y luego en Python.

## Integrantes y roles

| Integrante | Rol / tarea asignada | Aporte individual |
|---|---|---|
| Alexis Maier | Diseño de las plantillas, lógica condicional, filtro de consistencia, pruebas e informe | [calculadora-edad](https://github.com/alitomaier2010-netizen/calculadora-edad) |

## Requisitos e instalación

1. **Git** instalado para clonar el repositorio.
2. **Editor de código** (VS Code con extensiones de C/C++, o Visual Studio Community).
3. **Compilador g++** (MinGW-w64 / MSYS2) agregado al `PATH` del sistema.
4. Clonar y situarse en el directorio:

```bash
git clone https://github.com/alitomaier2010-netizen/calculadora-edad.git
cd calculadora-edad
```

## Estructura

```
calculadoraedad/
├── .gitignore
├── README.md
├── LICENSE
├── capturas/                 evidencias de ejecución (.png)
├── docs/
│   └── InformeProyectoCalculadoraEdad.pdf
├── proyecto_cpp/
│   └── calculadoraEdad.cpp
└── proyecto_python/
    └── calculadoraEdad.py
```

## Cómo ejecutarlo

```
g++ proyecto_cpp/calculadoraEdad.cpp -o proyecto_cpp/calculadoraEdad.exe
.\proyecto_cpp\calculadoraEdad.exe

python proyecto_python/calculadoraEdad.py
```
