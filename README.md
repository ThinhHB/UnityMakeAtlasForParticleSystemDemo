# Make atlas texture for ParticleSystem, reduce drawcall

This's a sample about how to make an Atlas texture for ParticleSystem in Unity3D, to reduce drawcall.
I wrote a [post](https://thinhhb.wordpress.com/2016/03/27/unity3d-optimization-make-atlas-textures-for-particlesystem-reduce-drawcall-why-not/) on my blog about how to do it, take a look for more details.

Here's the comparison between Using and NotUsing atlas texture for particleSystem:
-----
Not using atlas : it cost us **7 drawcall**

![Alt Text](https://cloud.githubusercontent.com/assets/9117538/14063525/0d0ce57a-f400-11e5-82cf-a745e2a362bf.png)
-----
Using atlas : **only 1 drawcall** for the same amount of particleSystem

![Alt Text](https://cloud.githubusercontent.com/assets/9117538/14063529/2a59ebdc-f400-11e5-9d45-e0f418396335.png)

