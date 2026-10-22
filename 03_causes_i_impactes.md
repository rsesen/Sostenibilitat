# Árbol de Problemas: [Nombre del Proyecto]

## 🍃 Efectos (Consecuencias)
*   **Efecto Final Grande**
    *   Efecto Directo A
    *   Efecto Directo B

## 🎯 Problema Central
> **[Escribe aquí el problema principal de forma clara y concisa]**

## 🪵 Causas (Orígenes)
*   **Causa Principal 1**
    *   Subcausa 1.1
    *   Subcausa 1.2
*   **Causa Principal 2**
    *   Subcausa 2.1
```mermaid
graph TD
    %% Efectos (Hojas/Ramas)
    E1[Efecto Secundario 1] --> EF1[Efecto Principal 1]
    E2[Efecto Secundario 2] --> EF1
    E3[Efecto Secundario 3] --> EF2[Efecto Principal 2]

    EF1 --> P[PROBLEMA CENTRAL]
    EF2 --> P

    %% Causas (Raíces)
    P --> C1[Causa Raíz 1]
    P --> C2[Causa Raíz 2]

    C1 --> SubC1[Subcausa 1.1]
    C1 --> SubC2[Subcausa 1.2]
    C2 --> SubC3[Subcausa 2.1]
```
