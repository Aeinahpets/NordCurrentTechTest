# Tech Test – Part 1: Sorting and Systemizing

Consistency is crucial in maintaining long-running projects. Without clear guidelines, a project’s file system can quickly become disorganized and difficult to navigate.  

---

## My Approach  

To improve structure and maintainability, I organized the project into clear, type-based folders:  

- **Animations** – all `.anim`, `.fbx`, and related files  
- **Materials** – material assets (`.mat`)  
- **Prefabs** – prefab objects (`.prefab`)  
- **Resources** – general-purpose assets that may be loaded at runtime  
- **Scenes** – all Unity scene files (`.unity`)  
- **Scripts** – organized further into subfolders (e.g., `Core`, `Environment`, `UI`, `Utilities`)  
- **Shaders** – all shader files (`.shader`)  
- **Sprites** – 2D images (`.png`, `.gif`, `.psd`)  
- **Textures** – texture assets for 3D models  

This structure ensures that when someone joins the project, they can quickly locate assets without confusion.  

---

## Naming Conventions  

To keep everything consistent across the project:  

- **Scripts & Classes:** `PascalCase` (e.g., `PlayerController.cs`)  
- **Folders & Assets:** `PascalCase` or `snake_case` depending on type  
  - Example: `Environment.shader`, `enemy_sprite.png`  

Following these conventions ensures readability, reduces ambiguity, and makes collaboration smoother.  
