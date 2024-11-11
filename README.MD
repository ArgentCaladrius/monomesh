# MONOMESH
MonoMesh is a series of Shader Graph graphs and subgraphs to allow for easy creation of 1-bit games with material-by-material control, avoiding the usual pitfalls of post-processing colour correction and the pixelation that comes with thresholding. This was created for my game [The White Owl](https://caladrius.itch.io/the-white-owl) as a tech demo for my next project, [The White Owl](https://caladrius.itch.io/sequestered).

*This is a package that will be under ongoing development for the foreseeable future, and some features may currently be missing, especially those regarding tinting as this was intended to be solely for black and white games first and foremost.*

[Example scene](https://img.itch.zone/aW1hZ2UvMTU4NTUzMC8xNDQ2Nzc3MC5wbmc=/original/4TwtcV.png)

## Features
- Conversion of standard lit surfaces to one 1-bit
- Main & additional light support
- Texture smoothing to reduce pixelation of final result
- Normal maps supported to adjust surface with lighting direction
- Stochastic terrain support for reduced texture repetition
- Screen-space dithering support for transparency
- - Includes light culling option to allow dithering to react to additional lights
- Sprites & billboarding
- Reflective material for 1-bit environment maps & skyboxes
- Animated television static shader

## Games
[The White Owl](https://caladrius.itch.io/the-white-owl)

*If you utilise MonoMesh for your game, let me know so I can include it on this list!*

## References
https://github.com/JuniorDjjr/UnityProceduralStochasticTexturingNode (Modified from source)
https://github.com/Cyanilux/URP_ShaderGraphCustomLighting (Custom lighting implementation)