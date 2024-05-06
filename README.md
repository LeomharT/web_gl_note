# Shader Syntax

Default shader

`fragment.glsl`

```glsl
void main()
{
    // rgba 
    vec4 color = vec4(255, 255, 255, 1);

    gl_FragColor = color;
}
```

`vertex.glsl`

```glsl
// Mesh porision * Window view position * Mesh.position 
gl_Position = projectionMatrix * modelViewMatrix * vec4(position, 1.0); 
```
