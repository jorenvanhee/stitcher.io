There's a Japanese word called "ma" or "間". 
The best way to translate it would be "gap" or "space between".
However, to fully grasp its meaning, I should give you an example.

Take a clay pot. What makes this pot "a pot"?
Since it's formed out of clay, you could say it's the clay that defines the pot.
On the other hand it's not the clay itself that gives the pot its function; 
it's the gap created by the clay that is the essence of the pot.

This gap gives the pot meaning, it gives it a function; 
this is a space created by the clay walls, and it's called 間.

Let's talk about object oriented programming.

{{ ad:carbon }}

I've been programming in OO languages for about eight years, 
three of which in college where I was taught the core of OO theory. 
Yet I must admit I find it difficult to coherently answer the question "what is OO?".

What makes an "object"? What is its purpose? 
Why do some think functional programming is superior?
These questions have been lingering in my head for the past few months.

I think I finally found an answer that satisfies my questions.

## Space between

Allow me to continue the example of the clay pot;
in it, objects are "the clay". 
They provide the structure that's essential for the pot — a program — to function.

Now whether you think of objects as "classes" as we know them in Java, C# and PHP;
or something else, is another matter.
But before diving further into that rabbit hole, let's hark back to our example.

Say you'd taken the clay and made a flat disk or a cube out of it;
your pot wouldn't serve its purpose.
Sure, given enough cubes, you're able to stack them in such a way that a new space appears between them.
Unfortunately, fill it with water and you'll notice it'll leak from many sides.

So what is this "space" in terms of object oriented programming? 
It's what gives objects real purpose.
Granted: the space between objects couldn't exist without them being there, 
though it's this space that gives them value.

The 間 of object oriented programming are the processes that work with objects.
They fill —&thinsp;they are&thinsp;— the gap between and within objects.

I believe this is the why functional programming is growing in popularity: 
functions are the gaps the make our program useful.
It's also the biggest pitfall of OO programming as we know it today: 
we think the objects themselves should provide the processes to work with them.

That's the pain so many people feel. 
That's the reason why classes grow so large and complex, why they feel rigid and sluggish.
That's the rabbit hole I was talking about earlier: 
inheritance is more often than not abused to create even bigger and more complex objects.

How you model these processes is up to you and your programming language. 
I believe you could very well model them as objects themselves, or you could use a functional approach.

Either way it's good to separate these two concerns: objects and processes. 
We should not wrongfully think of the clay as the pot as a whole. 

---

That was rather philosophical! 
If you made it this far though, I'd like to recommend you watch this very old talk by Alan Kay — he's the guy who invented the term "OOP".

What stuck with me most in his talk is that he says he didn't have Java or C++ in mind when he came up with object oriented programming.
It's an insightful and timeless talk, and I highly recommend it.

<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/oKg1hTOQXoY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

In closing, if you have any thoughts you want to share on the topic, 
feel free to reach out to me via [Twitter](*https://twitter.com/brendt_gd) or [e-mail](mailto:brendt@stitcher.io).
Thanks for reading!
