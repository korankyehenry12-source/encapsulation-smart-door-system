# Smart Door Access System for UMaT



## Overview

This project implements a Smart Door Access System for UMaT administrative staff, demonstrating the core OOP principle of Encapsulation. The system protects sensitive staff access codes using Python's access modifiers and the `@property` decorator.



## How to Run

1. Open the notebook in Jupyter, Google Colab, or VS Code.
2. Run the cells sequentially to see the class definition and demonstrations.

## Core Concepts

| Concept | Implementation |
|:---|:---|
| Encapsulation | Data and methods bundled with controlled access |
| Public Members | `s_name` — no underscore prefix |
| Private Members | `__access_code` — double underscore |
| Property Getter | `@property` with PIN check |
| Property Setter | `@access_code.setter` with length validation |

## Author
HENRY KORANKYE