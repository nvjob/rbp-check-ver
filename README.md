# Rain Benchmark
0.0.2.2 Beta 2018

https://rainbenchmark.pro

Benchmark for testing the performance of a personal computer. 
The benchmark consists of 5 basic tests. Has a small file size of 20MB. 


### Multithreaded CPU Benchmark

The principle of this test is to run several single-threaded processes performing complex mathematical calculations that load a single CPU thread by 100%. In the composition of 10 tests: 1T (1 process), 2T, 4T, 6T, 8T, 12T, 16T, 24T, 32T, 64T (64 processes).


### Average FPS: 30 / Max Polygons

Engine Unity, resolution 1250x670, vertex lit rendering, no physics. 
This is a test for GPU performance. The test is built on the Unity engine. At regular intervals, a new object consisting of 100,000 polygons is added to the scene. If the average FPS falls below 30, the test is completed.


### Min FPS: 30 / Max Physics objects

Engine Unity, resolution 1250x670, vertex lit rendering, mass 1, drag 0, gravity -9.81, sphere collider, scale 1. 
This is a benchmark for CPU + GPU performance. The test is built on the Unity engine. At certain intervals, a new primitive object consisting of 12 polygons, but with physics and a spherical collider, is added to the scene. The objects are in constant motion. If the minimum FPS falls below 30, the test is completed.


### Procedural World

Engine Unity, deferred rendering, real-time lighting and shadow, HDR, AO, MB, CCL, SMAA, volumetric fog, cloth physics, AI, NVGen. 
This is a benchmark for CPU + GPU performance. The test is built on the Unity engine and the NVGEN procedural generation engine. Depending on Seed, a different terrain is generated. The test uses a variety of different shaders, including a geometric shader DX11 model 4.0 procedural generation of grass and flowers. In the test, a large number of trees and various particles (clouds, fog, leaves, etc.). And also various post effects, lighting and shadows in real time. All this creates a significant load on the GPU. In the test, a large load on the CPU, as there is physics of tissue, wind, animation and adaptive artificial intelligence. The landscape is generated in real time.


### 15 Million Grass Blades

Engine Unity, deferred rendering, real-time lighting, HDR, NVGen. 
This is a test for GPU performance. The test is built on the Unity engine and the NVGEN procedural generation engine. The main load on the GPU creates procedurally generated grass (this is a complex geometric shader DX11 model 4.0). 
