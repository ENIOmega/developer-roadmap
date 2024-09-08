# Parallax

`Parallax` mapping is a method that combines the benefits of displacement mapping geometric and applies an approximation on it rather than actually rendering the geometery. A `displacement map` takes an image and applies a geometric shift to the mesh, which is then actually rendered. This process is can be quite graphically expensive, and in order to combat that parallax maps are used. Paralax maps approximate how light would behave if the object was actually 3D and then applies those approximations to a flat mesh, creating a similar effect to displacement maps but much less graphically intensive.

Here is a video that provides an extensive explanation of the subject:

- [A deep dive into mapping](https://www.youtube.com/watch?v=cM7RjEtZGHw)
