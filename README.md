# MeshReflectorMaterial
The MeshReflectorMaterial is a component provided by @react-three/drei library for creating reflective surfaces in a Three.js scene.

It mimics the behavior of a mirror or any reflective surface by reflecting the objects above it.

# Properties:

resolution: (Number) Determines the resolution of the reflection. Higher values result in better quality but may impact performance. Lower values sacrifice quality for better performance.

color: (String) Sets the base color of the reflective surface.

blur: (Array of Numbers) Configures the blur effect applied to the reflection. The first value represents the width of the blur, and the second value represents the height. Decreasing these values increases blur intensity while increasing them decreases blur intensity.

mixBlur: (Number) Adjusts the mix ratio between the base color and the blur effect. A value of 0 means no blur, while a value of 1 means full blur.

mirror: (Number) Determines how reflective the surface is. A value of 1 means full reflection, while a value of 0 means no reflection.
