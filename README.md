# Hi there 👋
I am a Lodz University of Technology postgraduate with passion for graphics programming and game development. I have received a Bachelor of Engineering degree in Applied Computer Science course with Computer Simulation and Game Technologies specialisation. While studying, I learned the basics of graphics programming with OpenGL. I also gained experience in more advanced usage of the API while writing my [Engineering Thesis](https://github.com/KamilMarel/Dispersion).
## **🔭 My projects**
### 🌈 [Light dispersion simulation](https://github.com/KamilMarel/Dispersion)
📄 An app that **simulates the light dispersion phenomenon**, created for my Engineering Thesis. Made with **OpenGL** and **C++**.

🎯 **The aim** was to reproduce the effect from the [Real-time Dispersion Rendering Algorithm based on Caustics Map and Single Charge Coupled Device Image Sensor](https://ieeexplore.ieee.org/document/10248466) **article by Yuanmeng Luo**. The process involved the article itself and its references (e.g. **Chris Wyman's** articles about the light phenomena simulation using **methods based on rasterization**).

⚙️ **Concepts and techniques used in the project:**
- **Dispersion maps**
- **Hierarchical caustic maps**
- **Photon buffers**
- **Photon splatting**
- **Image-space refraction through two interfaces**
- **Render-to-mipmap**
- **Layered rendering**
- **Transform Feedback**
- **Deferred shading**
- **Shadow mapping**
- **Mipmaps**

**More details** in the [project's repository](https://github.com/KamilMarel/Dispersion)
## 🤝 Projects I collaborated on:
### [💨 Winderer](https://github.com/AO247/Winderer)
🥈 **2nd place in Game Development category at [ZTGK](https://gry.it.p.lodz.pl/main/index.php/pl/) contest**  

A roguelike game made with **C++** and **DirectX 11**.  

**📜 My individual tasks:**
- **Particle system**  
Implementation of a simple **CPU particle system** used for basic effects like wind, fire and explosions. The particles could be emitted from a circle area or by using a sphere.
- **Physics system (own / Bullet Physics library / Jolt Physics library)**  
At the beginning I tried to create our own simulation system, but it came out that the game needed a more advanced approach to achieve the effects the team had in mind. Therefore I integrated the **Bullet Physics library**. Unfortunately the system had problems with specific collisions, so we decided to switch to **Jolt Physics**. Finally, the game enables the player to manipulate the environment by throwing the surrounding objects, and offers a simple destruction system.  

**📋 Shared tasks:**
- **Skeletal animation system**  
I helped with **diagnosing the animation visual problems**, then I decided to try to implement it by myself. My attempt was successful and allowed the further development.
