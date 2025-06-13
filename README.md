# litemelis

I mess around with graphics programming, game engine stuff, and the occasional compiler project. Mostly living in C++ land, with Vulkan as my graphics API of choice.

#

### What I’m Into

- Real-time rendering, shaders, and low-level bits  
- Building things from scratch (sometimes just to see if I can)  
- Compilers and language design

#

### Preferences

- Languages: **C++** **C#** **TS**
- Graphics API: **Vulkan**

#

### Right Now

I am currently working on a game engine called Litengine (currently private, but considering making public later). It is in the early stages right now, but progress is looking promising. More specifically, I’m working on the Vulkan renderer backend right now. I plan on adding real-time raytracing rendering techniques when the engine gets sophisticated enough, plus a high level language to make scripting easy. Potentially thinking of adding Mono for C# support too.  
Currently learning how a Vulkan game engine architecture would look like by following the Vulkan Guide tutorial.

#

###### I prefer the C++ Vulkan API wrapper rather than the C Vulkan API.

```cpp
cmd.bindPipeline(vk::PipelineBindPoint::eGraphics, readmePipeline);
```
