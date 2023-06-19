---
layout: sub-navigation
order: 1
title: Diagram test page
date: git Last Modified
---

## Diagrams

Examples taken from [Mermaid flowchart diagram documentation](https://mermaid.js.org/syntax/flowchart.html)

```mermaid
flowchart LR
    A o--o B
    B <--> C
    C x--x D
```


```mermaid
flowchart TD
    A[Start] --> B{Is it?}
    B -- Yes --> C[OK]
    C --> D[Rethink]
    D --> B
    B -- No ----> E[End]
```

Example taken from [Mermaid user journey diagram documentation](https://mermaid.js.org/syntax/userJourney.html#user-journey-diagram)


```mermaid 

journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me

```

