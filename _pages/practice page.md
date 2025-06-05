---
permalink: /day01/
title: "day01"
---

Day 1 notes

* Linear algebra is the study of vector spaces and linear transformations.
* A vector space is a set of elements (called vectors) which follow certain algebraic rules.  We will deal with that later.  For now note that a vector is a way of storing information!  Thus linear algebra is useful in many contexts because it allows us to analyze that information and derive useful results!
* In our activity we created a list of five numbers which indicated our preferences for various pizza toppings.  These formed vectors.  Their direction indicated a direction in `flavor-space'' and the length of the vector told us about how ``strong'' our preferences were.
* We focused on trying to tell how similar or dissimilar our preferences were from each other.  We settled on some sort of distance function (also called a metric) based on an extension of the Pythagorean theorem.    There are, of course, many other valid choices here.  An interesting way of doing this same sort of comparison (which is even simpler than distance) is by something called an inner product. An example of an inner product you are already familiar with (maybe) is the dot product!
* We looked at some other applications including image compression.  An image is stored as an array of information which can be thought of as a matrix which is a very important type of vector.  This matrix can be  factored in a manner that allows us to pick out the important quantities.  As a result we can reconstruct the picture approximately using a subset of information.
* You can play with this idea here:  https://timbaumann.info/svd-image-compression-demo/
*  Fourier series.  In this case our vectors were periodic functions.  We cared specifically about the vectors sin(kx) where k was a whole number:  $$\left\{ \sin(x), \sin(2x), \sin(3x), \sin (4x)\, \ldots \right\}.$$  These trig functions form something called a basis.
* We saw examples where we could  take a given periodic function (e.g., a wave) and write it as the sum of sine functions of various periods.  taking apart a complicated thing as a sum of simple things is extremely powerful since it (among other things) greatly simplifies how we store and share information.
* For examples of this in the case of Fourier series check out the fun apps at https://www.jezzamon.com/fourier/
* We ended class with perhaps the most exciting topic:  Solving systems of linear equations! 
* Linear equations correspond to (hyper)planes in space.
* Systems of linear equations have 0, 1, or infinite solutions.  These correspond to how the hyperplanes can (and cannot!) intersect.
* If a system has at least one solution we call it consistent.  If it has zero solutions, we call it inconsistent. 