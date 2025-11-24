---
title: '' # Lasciamo vuoto come richiesto
date: 2023-10-24
type: landing # FIX CRITICO: Cambiato da 'page' a 'landing'

design:
  spacing: '0rem' # Rimuove la spaziatura predefinita tra i blocchi

sections:
  # SEZIONE 1: WINE
  - block: markdown
    id: wine-section
    content:
      title: 'Wine' # Titolo H2/H3
      text: |
        Pictures from our family vineyard “Le Due Sörele” (The Two Sisters)

        ---
        

        {{< figure src="/uploads/Wine_3.jpg" >}}
        {{< figure src="/uploads/Wine_2.jpg" >}}
        {{< figure src="/uploads/Wine_1.jpg" >}}
    design:
      columns: '1'
      spacing:
        padding: [0, 0, 4, 0] # Padding per separare Sketches

  # SEZIONE 2: SKETCHES
  - block: markdown
    id: sketches-section
    content:
      title: 'Sketches'
      text: |
        To calm my nerves

        ---
        {{< figure src="/uploads/Sketch_1.jpg" >}}
        {{< figure src="/uploads/Sketch_2.jpg" >}}
        {{< figure type="portrait" src="/uploads/Sketch_3.jpg" >}}
        {{< figure src="/uploads/Sketch_4.jpg" >}}
        {{< figure src="/uploads/Sketch_5.jpg" >}}
    design:
      columns: '1'
      spacing:
        padding: [0, 0, 8, 0] # Padding per il fondo pagina
---
