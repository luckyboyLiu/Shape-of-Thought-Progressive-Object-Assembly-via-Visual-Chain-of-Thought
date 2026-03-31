### **Figure R1. Expanded single-view qualitative comparison.**

Additional single-view qualitative examples across keyboards, beds with storage compartments, refrigerators, faucets, and headphones. Compared methods frequently exhibit degenerate geometry, collapse, missing or miscounted parts, and disconnections, whereas SoT more consistently preserves numeracy, attribute binding, attachment, and overall topology. Blue boxes mark structural/detail errors, red boxes mark count or attribute errors, and green boxes mark connectivity or part-dislocation failures.

<img src="https://github.com/user-attachments/assets/8ee20df7-cc32-4ae6-a78f-23dc7ddf0084" style="width:100%; max-width:900px;" />

### **Figure R2. Representative multi-view SoT traces across viewpoints.**

Representative multi-view rendered traces for two prompts (scissors and faucet) under front/left/right/back view-conditioned descriptions. The part-by-part traces remain coherent across viewpoints, preserving part count, attachment, and relative spatial layout while adapting the intermediate states to each view. These examples illustrate the rendered-domain multi-view setting introduced in the rebuttal and show that the same trace formulation can extend when additional view supervision is available.

<img src="https://github.com/user-attachments/assets/b497702d-011b-4102-a29b-65841d22899e" style="width:100%; max-width:900px;" />

<img src="https://github.com/user-attachments/assets/b5c9dbc6-9f13-4301-82f7-39394e842c50" style="width:100%; max-width:900px;" />



### **Figure R3. Representative zero-shot multi-view failure case.**

A representative failure case from Bagel-7B-SoT (Zero-shot) under multi-view rendering. Although the trace appears plausible from the canonical/front view, the left/right views reveal an incorrect side profile of the backrest (green boxes), highlighting residual difficulties with view-sensitive geometry, self-occlusion, and partial 3D ambiguity. This example clarifies the remaining boundary of the original single-view SoT model when evaluated beyond the front view.

<img src="https://github.com/user-attachments/assets/de54e0cd-5fcc-4777-ac95-f6c653ea8ad9" style="width:100%; max-width:1300px;" />
