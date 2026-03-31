### **Figure R1. Diverse qualitative lifting proof-of-concept results.**

We show SoT-generated masks (Left, pink) and the corresponding meshes lifted by off-the-shelf SAM 3D (Right, gray) across multiple categories, including sword-like objects, keyboards, drawers, chairs, headphones, and cabinet-like objects. The lifted meshes broadly preserve coarse part layout and global geometry, suggesting that SoT traces can support downstream lifting in some cases. Fine details may still be smoothed or lost during lifting, for example keyboard keys, so these results should be read as a qualitative lifting proof-of-concept only, not as a claim of direct 3D generation.

<img src="https://github.com/user-attachments/assets/db6f5c29-a043-44a6-9b3b-32cf1587005f" style="width:100%; max-width:900px;" />

### **Figure R2. Single-case qualitative lifting example.**

Left: a SoT mask with clear part boundaries and attachment structure for a chandelier-like object. Right: the mesh produced by off-the-shelf SAM 3D. The lifted result preserves the global arrangement of the central stem, side arms, and lamp shades, illustrating that some SoT traces can support downstream lifting. As in Appendix I overall, this is a qualitative lifting proof-of-concept only, not evidence that SoT itself outputs editable 3D geometry.

<img src="https://github.com/user-attachments/assets/33e77dec-e5e6-4090-804c-46e093d994e7" style="width:100%; max-width:900px;" />

