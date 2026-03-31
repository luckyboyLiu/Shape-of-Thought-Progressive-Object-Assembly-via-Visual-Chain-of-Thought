### **Figure R1. Diverse Qualitative 3D Lifting Results.**
We visualize the SoT generated segmentation masks (Left, pink) and the corresponding 3D meshes lifted via SAM 3D (Right, gray) across various categories. The results highlight SoT’s ability to maintain geometric rationality across varying complexities. Note that while the lifting pipeline reconstructs complex organic shapes like the sword’s tentacles, it may smooth out high-frequency details like the keyboard keys due to resolution constraints, despite these structures being explicitly segmented in the SoT source mask.

<img width="5644" height="3573" alt="4a583304531f44f35ae698c425fca844" src="https://github.com/user-attachments/assets/db6f5c29-a043-44a6-9b3b-32cf1587005f" />

### **Figure R2. Qualitative 3D Lifting.**
Left: The generated image from SoT exhibits clear structural boundaries and distinct part separation (visualized via SAM masks). Right: The resulting 3D mesh lifted using SAM 3D. The successful reconstruction verifies that SoT traces possess the necessary geometric integrity and component distinctness to support downstream 3D applications.
<img width="2389" height="959" alt="7f65b7fb1f6fab44970c7d003006449d" src="https://github.com/user-attachments/assets/33e77dec-e5e6-4090-804c-46e093d994e7" />
