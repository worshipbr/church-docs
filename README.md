# SIGI

Este repositório tem como finalidade explicar de forma objetiva quais as funcionalidaes presentes no SIGI (Sistema de Gerênciamento de Igrejas)

### Diagrama ER

```mermaid
---
title: Administração de Visitantes
---
erDiagram
    CHURCH ||--|{ USER : contains
    USER }|--|| ROLE : assign
    CHURCH ||--o{ GUEST : recieves
    GUEST ||--o{ COMPANION : brings
    CHURCH ||--|{ DEPARTAMENT : has
    GUEST }|--|| DEPARTAMENT : integrates
    USER }|--|{ DEPARTAMENT : leader
    CHURCH ||--|{ NOTE : show
```

---

## title: Administração de Visitantes

```mermaid
erDiagram
CHURCH ||--|{ USER : contains
USER }|--|| ROLE : assign
CHURCH ||--o{ GUEST : recieves
GUEST ||--o{ COMPANION : brings
CHURCH ||--|{ DEPARTAMENT : has
GUEST }|--|| DEPARTAMENT : integrates
USER }|--|{ DEPARTAMENT : leader
CHURCH ||--|{ NOTE : show

```
