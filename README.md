<div align="center">
    <p align="center"> <i> 💜 Ｇｏｄｏｔ Ｒｅｔｒｏ 💜 </i> </p>
    <p align="center"> <i> Ｏｌｄ－ｓｃｈｏｏｌ ｓｈａｄｅｒ ｐａｃｋ </i> </p>
    <img src="https://user-images.githubusercontent.com/56614267/187816590-4fc9e419-84ba-4082-bfaf-e6f02001824d.png" alt="Logo" align="right" width="50%"></img>
    <img src="https://img.shields.io/badge/license-CC0%20&%20MIT-b339e3?style=flat-square" align="center"></img>
    <img src="https://img.shields.io/github/stars/Ahopness/GodotRetro?color=b339e3&style=flat-square" align="center"></img>
    <img src="https://img.shields.io/github/forks/Ahopness/GodotRetro?color=b339e3&style=flat-square" align="center"></img>
    <img src="https://img.shields.io/badge/version-3.5.0-b339e3?style=flat-square" align="center"></img>
    <img src="https://img.shields.io/github/repo-size/Ahopness/GodotRetro?color=b339e3&style=flat-square" align="center"></img>
    <img src="https://img.shields.io/github/last-commit/Ahopness/GodotRetro?color=b339e3&style=flat-square" align="center"></img>
    <img src="https://img.shields.io/badge/Twitter-Ahopness-b339e3?style=flat-square" align="center"></img>
    <hr>
</div>

## Summary

* [About](#about)
* [License](#license)
* [Shaders](#shaders)
* [Installation](#installation)
* [Examples](#examples)
* [Features](#features)
* [Limitations](#limitations)
* [Credits](#credits)



## About

**Godot Retro** is a collection of shaders for godot, with various ports of shaders from *ShaderToy*, *Unity* and The *Book Of Shaders*. 



## License

* Shaders

All shaders are licensed under **CC0**, with the exception of the *Glitch* and the *NTSC Basic* shaders, which are licensed under **MIT**. 

* Example Scenes

*Models*, *scripts*, *textures* and *sounds* are all under **CC0**.

The *shrWind* shader, used in map 4, was made by **Maujoe** and licensed under **MIT**.



## Shaders

- Glitch

- NTSC Basic

- Grain

- Simple Grain

- Jpeg Compression

- Dithering

- Lens Distortion

- NTSC

- Simple Glitch

- TV

- VHS

- VHS Pause

- Accurate CRT

- B&W

- Better CC

- Blur

- Color Precission

- Sharpness

- Hello World

- Hello World 2

### Recommendation

The shaders look their best when they are used together!

**Example :**

This scene uses the following combination : **Lens Distortion + Grain + TV**

<img src="https://user-images.githubusercontent.com/56614267/138868860-0a105613-279c-4918-84b1-a1208ad206f8.png" width="50%"></img>

And this scene uses this combination : **Lens Distortion + Sharpness + NTSC**

<img src="https://user-images.githubusercontent.com/56614267/138868037-8d0ec41a-9e59-47ec-9873-fc9a2ff014b9.gif" width="50%"></img>


- Tip 1 : **Sharpness** is a must have when using any of the *TV*, *VHS* or the *NTSC* shaders for getting a more realistic retro effect!

- Tip 2 : **Lens Distortion** and a high FOV looks like the old MTV 2000 blumbers aesthetics if used correctly!

- Tip 3 : Be careful with **Grain**! It can get very messy if you aren't careful!

- Tip 4 : All shaders can be used beyond their default range values, just open the shader code and adjust the numbers inside the *hint_range()* function in the variables section.

- Tip 5 : **ALWAYS** check the headers of the shaders you are using, there's information about the *compatibility*, *credits* and *licensing*!



## Installation

**How to use a shader included in this collection in your projects** :

1. Copy the *GodotRetro* folder to your project (can be added anywhere in the filesystem)


***For normal shader*** :

2. Just add the shader to a *ShaderMaterial*.


***For screen space shaders*** :

2. Create a *ColorRect* and make it a *FullRect* in the *Layout* options

3. Assign the preferred shader to the *ShaderMaterial* property of the *ColorRect*.


**Example :**

![example](https://i.imgur.com/sSti5i8.png)


**You have successfully applied your first shader!!** Have fun!


### DISCLAMER :

- To use 2 or more shaders at the same time, you gotta use a BackBufferCopy set as Viewport for each shader.
- 
- For UI, make sure to set it above the shaders for them to be affected by the shaders for more uniformity and immersion.



## Examples

5 free and easy to learn example scenes are included in this collection.

<div align="center">
   <img src="https://user-images.githubusercontent.com/56614267/138868105-6b24ea23-ba13-4160-b936-35a43f9993d5.gif" align="center" width="30%"></img>
   <img src="https://user-images.githubusercontent.com/56614267/138868168-803a3cd0-82c9-4b83-8e1e-9bc614d5681c.png" align="center" width="30%"></img>
   <img src="https://user-images.githubusercontent.com/56614267/187816644-c782709d-87d3-4d74-8b16-659a700fb408.png" align="center" width="30%"></img>
</div>

**General controls**:

|    ESC    |
|-----------|
| Quit Game |

**Map 1 controls**:

|    W   |     A     |     S     |     D      |     E     |     Q     | Shift |
|--------|-----------|-----------|------------|-----------|-----------|-------|
| Foward | Turn Left | Backwards | Turn Right | Walk Left | Walk Left |  Run  |

**Map 4 controls**:

|     A     |     D      |
|-----------|------------|
| Move Left | Move Right |



## Features

 - **22** easy to use godot shaders

 - 5 well done **example projects**



## Limitations

Unfortunately, some shaders arent 100% perfect.

 - Some shaders may not work in GLES2, please check the respective shader's header inside the shader code tab for more information!



## Credits 

Shaders ported by : **Ahopness ([@ahopness](http://twitter.com/ahopness "My Twitter Account"))**

*B&W* shader was originally made by : **demofox (ShaderToy)**

*Color Precission* shader was originally made by : **abelcamarena (ShaderToy)**

*Jpeg Compression* shader was originally made by : **paniq (ShaderToy)**

*Better CC* shader was originally made by **Wunkolo(ShaderToy)**

*Lens Distortion* shader was originally made by **jcant0n(ShaderToy)**

*Sharpness* shader was originally made by **Nihilistic_Furry(ShaderToy)**

*Grain* shader was originally made by **spl!te(GitHub) & martinsh(Personal Blog)**

*Simple Grain* shader was originally made by : **juniorxsound (ShaderToy)**

*TV* shader was originally made by : **ehj1 (ShaderToy)**

*VHS* shader was originally made by : **FMS_Cat (ShaderToy)**

*VHS Pause* shader was originally made by : **caaaaaaarter (ShaderToy)**

*NTSC* shader was originally made by : **ompuco (ShaderToy)**

*NTSC Basic* shader was originally made by : **keijiro (Github)**

*Glitch* shader was originally made by : **keijiro (GitHub)**

*Simple Glitch* shader was originally made by : **Gaktan (ShaderToy)**

*Blur* shader was originally made by : **jcant0n (ShaderToy)**

*Hello World* and *Hello World 2* shaders were originally made by : **Patricio Gonzalez Vivo** 

