# 4D Minecraft clone
This is a 4D clone of Minecraft written entirely in x86 assembly. Note that this is only a hobby project and it couldn't be finished unfortunately :(<br>
Some notable implementations are:
<ul>
  <li>
    Assembly:<br>
    <ul>
      <li>Multi-threading for separating physics, graphics and chunk loading processes</li>
      <li>OpenGL loader and handler</li>
      <li>Audio mixer for resampling and playing multiple sounds at the same time</li>
      <li>Math library for rendering and calculating the 4D world</li>
      <li>User interface with highly configurable elements, written in an object-oriented manner</li>
      <li>Collision detection and resolution in 4D</li>
    </ul>
  </li>
  <li>
    OpenGL:<br>
    <ul>
      <li>Rendering the hyperplane-world intersections</li>
      <li>Deferred rendering for reusing the intersection geometry and also post-processing</li>
    </ul>
  </li>
</ul>

<br>

If you want to try it out yourself, you can do so by executing <br>
```test.exe```<br>
in the game_files folder.<br>
<br>
Alternatively, go to the ```src``` folder and type:<br>
```morb```<br>
<br>
If you want to build the project with compiler optimization turned on, type<br>
```morb harder```<br>
instead.<br>
<br>
The program needs
<ul>
  <li>Windows 7 or above</li>
  <li>A CPU with AVX2 support</li>
  <li>A GPU with OpenGL 4.6 support</li>
</ul>
to run.<br>
<br>
NOTE: The project is not very stable on Intel GPUs at the time of writing. <br>
<br>
<br>
## Gallery

![gaymplay2](https://github.com/user-attachments/assets/4312d276-3c41-4a6b-9104-c0a6f9ceacd6)
