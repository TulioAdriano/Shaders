# Shaders
This is a collection of CRT Shaders for RetroArch. They're made based on the original shaders that are downloaded with RetroPie, however with the help of Falco Girgis from Elysian Shadows team, I've tuned these shaders a lot so that the cathode ray blooming looks more realistic, and so that they add the blurring inherent from composite signal which makes pixel blending possible, and was highly used to generate extra colors on the Sega Genesis and other systems. 

I labeled the initial upload as Raspberry Pi because they're known to work on it, and I have been able to use them on the PC version of retroarch as well, however they don't seem to load on the NES Classic for example. So either I need to figure out how to fix them to work on both, or create modifications tailored to the NES Classic, based on their existing shaders. 

# About me
Many know me as the creator of Pier Solar and the Great Architects for Mega Drive, and for my projects making hardware synthesizers out of video game chips. I don't know anything about GLSL other than what Falco showed me and by poking around, so this code may look atrocious to some people. My background is in C# and I fiddle with embedded C++ for Arduino, but then again I am not a C++ programmer, just a programmer with no fear of exploring. 

# Want to help?
Help is welcome! My dream is to create a shader that can also simulate the NTSC artifacts such as luma leak into chroma, but I have too little knowledge of GLSL to be able to come with it on my own. I normally enable the CRT filter with addition to Genesis Plus Blaarg NTSC simulation for composite and I get a result that is very close to a real CRT. 
