**Test environment (as run):**  
- GPU: NVIDIA RTX 3050  
- CPU: 13th Gen Intel i7-13700  
- RAM allocated to Minecraft: 4 GB  
- Minecraft version: 1.21.5  
- Modpack version tested: 4.4.0  
- Modpack defaults used: Render Distance 14, Simulation Distance 5, Fancy Graphics, All Particles, Fancy Clouds, Smooth Lighting, Entity Distance 100.


**Methodology:**  
Measured *average world creation time* across six seeds (named `hydrogen1` … `hydrogen6`) and recorded approximate average in-game framerate. "World creation time" here refers to the time measured for creating/loading a new world with the above settings (results and raw numbers below).

**Results (raw samples and averages):**


| Metric | HydrogenPack (modpack) | Vanilla |
|---|---:|---:|
| World creation samples (sec) | `0.866, 1.033, 0.800, 0.633, 0.633, 0.900` | `0.933, 1.996, 1.666, 1.666, 1.600, 2.000` |
| [Average world creation time](https://youtu.be/F086PxhO3bA) (s) | **0.811** | **1.644** |
| Time change | **−51%** | — |
| [Approx. average FPS](https://youtu.be/PbAtQNDmbRM) | **~1800 fps** | **~700 fps** |
| FPS change | **+157%** | — |

**Analysis:**  
- On this hardware and with 4 GB allocated, Hydrogen reduced the average world creation time from **1.644 s** (vanilla) to **0.811 s** — a reduction of approximately **50.7%**.  
- Average framerate observed in these tests increased from ~700 fps (vanilla) to ~1800 fps (Hydrogen), an approximate **157%** increase. 
