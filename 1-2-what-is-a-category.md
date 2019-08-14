# 1.2 What is a category?

Moving toward the mathematical, rather than the philosophical, side of things.

The major tools in our arsenal are:
1. Abstraction
2. Composition
3. Identity

Abstraction involves getting rid of details. Forget about the assembly language of what you're trying to accomplish, not only in programming, but in the math as well: get rid of unnecessary details. Getting rid of unnecessary details suddenly makes two distinct objects the same. Two billiard balls may have the same color, but different atomic configuration, but you don't care when you're actually playing pool. This is why we have a notion of identity, the third tool above.

There is strict identity: replacing one thing with another and not having any difference, and there's practical identity: identical for all intents and purposes. There's an important distinction between "these are the same" and "we'll call these the same." A whole theory is being developed around this very concept of identity called homotopy type theory, dealing with what is equal, or practically equal (called "isomorphic"). Is isomorphism and equality the same? Should we treat it the same?

Identity and composition define category theory, that's all there is.

With these tools, you're ready for your first definition: a category.

It cannot be defined cleanly and precisely, so imprecise language will be used. It's not enough to say a category is a "set" of objects, because that's not always the case. Sets are not the end-all-be-all, there are bigger things. What is a set? A thing with a bunch of elements, defined by membership. Sets can be built with sets to get sets of sets. So then how do you define a set? By which members it has.

Sets can be memners of themselves or not. A set of dogs is not a dog. Take a set of all sets that are not members of itself. Is this set a member of itself? If it isn't, it shouldn't belong to the set, if it is, it should. You have a paradox. You can't have a set of all sets, because it would necessarily have to be its own powerset. All this is stuff set theorists lose sleep over, but category theorists don't worry about it, what they worry about is categories.

A category consists of objects and a set of arrows, or morphisms. A morphism/arrow is something that goes between two objects. If you have an object `a` and an object `b`, then you have an arrow `f` between them:

```
a ---> b
   f
```

But what's an object? It's a primitive with no internal structure. Like a point, it has no properties. 

What's a morphism? Also a primitive. It has no properties, except that it has a beginning and an end.

10:39
