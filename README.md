### **Figure R1. Expanded single-view qualitative comparison.**
Across diverse categories and structural constraints, we provide a larger stratified gallery covering not only numeracy but also attribute binding, connectivity, and topology. The results show that SoT consistently improves structural correctness and avoids common failure modes such as degenerate structures, missing components, and disconnections.
<img width="5588" height="4729" alt="image" src="https://github.com/user-attachments/assets/b0993d29-c7c5-4233-a3de-62fe88571431" />
### **Figure R2. Multi-view evaluation and pilot multi-view extension.**
We evaluate all methods under a four-view protocol (front/left/right/back) and introduce a pilot multi-view finetuned version of SoT. Even without multi-view training, SoT (zero-shot) substantially outperforms baselines on structure-related metrics. With multi-view supervision, SoT further improves across CN, AF, CP, and VT, demonstrating that the framework extends beyond the single-view setting and mitigates occlusion-induced errors.
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/dcbb725d-8f76-43a4-98e1-f233305fb1f5" />
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/60612c92-2814-4185-a838-ae9821293876" />
### **Figure R3. Representative multi-view failure modes.**
We show cases involving self-occlusion, thin structures, and ambiguous depth, where single-view supervision is under-specified. Multi-view supervision reduces many of these errors, although some challenging cases still remain.
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/bf56f978-0dc5-42d4-ae80-a3d620423ee5" />
