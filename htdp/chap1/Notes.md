#Notes on Chapter 1 - Fixed Size Data

#### Rules of thumb 
1. Simplify the outermost and the left most sub-expression that is ready for evaluation
2. Raise input errors by calling the error function
3. When a problem refers to distinct tasks of computation, a program should consist of one function per task and a main function that puts it all together. 

#### Primitives
1. Functions that compose images—requires the introduction of one new idea: the <b>anchor point</b>. An image isn’t just a
single pixel; it consists of many pixels. Specifically, each image is like a photograph, that is, a rectangle of pixels. One of these pixels is an implicit anchor point. When you use an image primitive to compose two images, the composition happens with respect to the anchor points, unless you specify some other point explicitly:
