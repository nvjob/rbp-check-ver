# Rain Benchmark
0.0.2.2 Beta 2018

https://rainbenchmark.pro

Benchmark for testing the performance of a personal computer. 
The benchmark consists of 5 basic tests. Has a small file size of 20MB. 


### Multithreaded CPU Benchmark

The principle of this test is to run several single-threaded processes performing complex mathematical calculations that load a single CPU thread by 100%. In the composition of 10 tests: 1T (1 process), 2T, 4T, 6T, 8T, 12T, 16T, 24T, 32T, 64T (64 processes).

![GitHub Logo](https://lh3.googleusercontent.com/LsuAhF0y4d1yyYoucwMoViv0VBj-XCYpsa3IXDZKfWajQKhVSxrCsb3Bn05P1GeD9sQwWnrv69_3fO8TZixxpoXkbHCLVGsUUEgdL0m0FGKtjNPz2KZCzVmwn5D-LDhq0FxZY9B-0GOc-_ukoKN7EOLncysGJun0oR8k9rkK00ZLFN7wPndxkd4YCcg7_L-i92CZRsia3AmZ7ipZWMcHgPFg51D97DvrMpBFSgjAOq5zyJX0s7IrRcmAE1Alszq6HCuXNo4i-GOOIrd8x2iasX5eiy9rG4GqYcLw-1kxihrVZFvj5IIbuN5P_V5u8QkRF42wfC7eUWktLKmHF-EVlt6Rch5CgIfyyarVAZDG5fcYDjeFrpJss8oplSPf5nkksbHsYnqiH3FG_UtiuPlCUKUZwKcUkh34G-8o_4xVO_1bqroCVYRLDfOEVDDAAaxRRKsTxQaBbYKfguO13aHst-lxFNST2qF1c1wM8TGFFKefn9oeRrnNTOZNeVSfvCHghbGvIJnd7rw4AYDfxWprbjyvobHVNT2ccDVn000zeNcE68JTuWXGwPOPhZAdmHNZRujDYrUsY8j2BXItf1aN5VJCIgIBhRc0HxsVGys=w850-h657-no)


### Average FPS: 30 / Max Polygons

Engine Unity, resolution 1250x670, vertex lit rendering, no physics. 
This is a test for GPU performance. The test is built on the Unity engine. At regular intervals, a new object consisting of 100,000 polygons is added to the scene. If the average FPS falls below 30, the test is completed.

![GitHub Logo](https://lh3.googleusercontent.com/YZ4q_Wo8l3tqOx9QR9XNnkJizhCXg-HVrm-DTvuyCZu_yk7E47hv5LlP5yGN5eCQVe0B6TVqVaAY1Flx_LVHA1xxD-EvBDYwI0I6OnL5jTJYQd0WNtyf5k7rhEE35nZsCZf8kvp-Q1LptGmMXMHs5kHrQRye4FT5zYovf61ns9NtskfF_FtPP6TmWoJM1QI2CtIRU5LSQklHhwN4csNJ8_Zc1q3RqiKZQVLTWfn_qgF0EM5D9QNKKEAA-ym9BpcIr-eIBwNcmLSHy9g64GXm4bW0WXh89Mhem6Hk2LNkkhvOTE08nY3a0lR8-0IOVmnJsBWQ_OUVwEIfyYMvmYTdEJEMG4uXq6dBY_dGU-djVpwZxNutN4KbrWG5_x7Kl75dnJB8RWjbCkwGhTrhEjQzLWNk7aqy5KvuxSH4yzu2yUptD_s6t4xq8m-bozl66C1LvWjdgnfgVqWc6BFahulKFv91C6RAwwrTvBAskZALTZY-Y4lARlUngpC-YkzbjgUr-clXrlyhdpnfcrkBFHNx-gAdl-CRez05ZQwswGlbEDIG0fon0101SKlO7-eVWWBEy1dvymUdT2jWJJ7OWokKKuQB719TMKRi1MGJ1RA=w850-h456-no)


### Min FPS: 30 / Max Physics objects

Engine Unity, resolution 1250x670, vertex lit rendering, mass 1, drag 0, gravity -9.81, sphere collider, scale 1. 
This is a benchmark for CPU + GPU performance. The test is built on the Unity engine. At certain intervals, a new primitive object consisting of 12 polygons, but with physics and a spherical collider, is added to the scene. The objects are in constant motion. If the minimum FPS falls below 30, the test is completed.

![GitHub Logo](https://lh3.googleusercontent.com/t-RTSP3BLcuf7qQshgkHbdgYtdZM1dyTtm0MXtQ4h1YUL3ccfA0RquS1ojl_7wxeUqJM0OG5dwKUFMlAOMWCWg3DvN4mr7-mdlmOrKlt6WJ0lOD7zshOhrT-GXauw9QHiDXnuEW_tuXWNtXe58CMQyAuXdJYqW2v18hHSIuRQNNGqZVhL1Gnt76Wcp8fVFSBStCyz_krcATRTT0rw-ohfd34Mpre6Fqqf3RjiQKrj-rwjMc3ETUjb35xBBf8xypG05kQRdpfXT5kcLXe_V1Cp3tyaSIfsR72l06pVDadmoMVVhGUo0If7wEuYZDvkCBZ2dvb883VL-5vDc6AcjnUCkzqvgq5nSxBJAgPDw9BHNL7fZz8J9feoN4L0VNJbwf1HYiizh4wcr17E93AuRbgQ1aodjZQkSaYZYT2yExKlxTGy7wZejcdwwSm6_r0OIxIA_5MMBtRyOdmE7SIUWd61Ol8rOHWOymzJNxiZPvkdMucbbqpohXmtJYbN7a5LH1ykJ03vBfvNmdJ8NQ_OB7Fnl8BZOaU_kFVGUW47Bvzc-bJWI3uHUu7xcrymUkK6DEOeqIKZVBHYXnHE3u36Cdedj6G0rrjyrP0QwvLDTg=w850-h456-no)


### Procedural World

Engine Unity, deferred rendering, real-time lighting and shadow, HDR, AO, MB, CCL, SMAA, volumetric fog, cloth physics, AI, NVGen. 
This is a benchmark for CPU + GPU performance. The test is built on the Unity engine and the NVGEN procedural generation engine. Depending on Seed, a different terrain is generated. The test uses a variety of different shaders, including a geometric shader DX11 model 4.0 procedural generation of grass and flowers. In the test, a large number of trees and various particles (clouds, fog, leaves, etc.). And also various post effects, lighting and shadows in real time. All this creates a significant load on the GPU. In the test, a large load on the CPU, as there is physics of tissue, wind, animation and adaptive artificial intelligence. The landscape is generated in real time.

![GitHub Logo](https://lh3.googleusercontent.com/7-fM9wmg_FE1gnxdZHVw92sFM1qxk8KR2jp3aVvb9wQGfNH0fpq5g_mE5-Pi6u35ozoK_XZJR_hPeSGGNaMASmj6sG_PbAEGLpZ33Zjn3Od_Il9XmI4mnux565taT3hd3Iq2kGt8yLsPn63I61hy8sLwxhQ5oxpKPNcbWR1LY7D8f5y81bPLXfqJMketuqCocatrKMBZ5flgBqhQ8CcXJvgTmb9EHYd8CEwNZxCmYJzJvonRFMgIkkPDy9plpXtn7UOuPWRKHjjALMW5n3_gP2vU_zY2WkT7HU2qkWal_zCoMGDf49fJM3rbLuJgCGw-21D8eJ-ZEHzkC8rvUwdhbr3I4e2nmZmVOZIKPUAf_fid7wUHdKigkTfZdW1nutjMG8aMEifRzg7y0E7HKl1Zzi2KyHAG9Bnokg2YXceopjgCZ1sG_h5QqkvCDqb-jCUKB_YKXaZOpSUHXXFh_fqecC7GRsMpXU5EuubO2Qu20ZVqYJ09oX--21aDIf8sEm-3h1TdZUbwnayneiIXRkdxLo35jz6DI_G0u4d97SayLsfkZWwcEkFEVzKT9SvKEJmqwuGkoVJRjzygOksKVGoTTWB_jh0ls4aQzvWerUI=w850-h478-no)


### 15 Million Grass Blades

Engine Unity, deferred rendering, real-time lighting, HDR, NVGen. 
This is a test for GPU performance. The test is built on the Unity engine and the NVGEN procedural generation engine. The main load on the GPU creates procedurally generated grass (this is a complex geometric shader DX11 model 4.0).

![GitHub Logo](https://lh3.googleusercontent.com/M3C0bHqOPC-6NSKvoOT1F-ZQn8Eo9AOg2kz-J7s0qiY62oDZejAP5Oy0yT4Mxu99wN7W4xMuFsy7JxOd_AFYmkCXRKnxXq8ML-7OEKdZf_4i6sZd_XDR4fsr3dbd8415dQH8krtC6jYTwV--wIIuEK7DuUXBnTfoU1AibY-aQSvyG-mkbGJ3swgWFMoRseTtRzcUke-IkcGu8hOWQnm0f0LNZ2s3uzWaxkIQQKa9m1Ww-mvWmE3YuTOProLtWvx0OQZ6ZuWwJyip30Lub-4dKKu8ZdlI8yiz7bNhxs55hf6NYE-Qfx_0K8doLMWPo5WnIYQq_I1c4CeKTCX1nOJ1Epf8g05qy3jS8RNTu9coyx9_k5BXZhFsJDQ1g1bKH0ovtLW7doqabfHnHR1m5iTlf4wuKwl2-Y8rR8PCDe5hNTrKbjeKFfg9M0PAdaurtj2irZVrSe-aODRD7roHxEVQ_pvTsP-g37x6HDwhVxLux_pSZi1XnhqN5FaxjVSy-ZOAuG9cehf-Cf6SmkJO58VyA-7zGbr-BSP7MOPaqmrk4juZgBVNjBzhGr3Q9Alow_ismTptXMpUwanaHlo4SQbAvLo5PGqKQdVKP5IoHtk=w850-h478-no)


https://www.youtube.com/watch?v=CGCWCQpIavA

https://www.youtube.com/watch?v=e3GtYZBEm08

https://www.youtube.com/watch?v=wj63WRrRjEo
