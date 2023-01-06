# The-Idea-of-Non-Integer-Times-Differential
The idea from half time differential and some more.

I thought of non integer times differential before, but I didn't figure out how to do that. 
<br/>This time, an new approach came to my mind. I believe it's possible, but I don't want to really study it myself, because I'm too busy recently.

The idea is like:
<br/>Let's define a function first. Since I prefer program-like way to convey, this definition looks like a piese of code.
<br/>Define: dif(some expression, differential times) to mean, differential the expression by the given time. Notice, the time number doesn't have to be integer.
<br/>With this definition, 
<br/>dif(x*x, 1) === 2x, which is the same as f(x) === x*x, then f'(x) === 2x. When the second parameter of dif function is 1, it works exactly the same as a normal differential we saw everywhere.

With the definition and trigonometric functions, things get interesting:
<br/>dif(sin(x), 1) === cos(x)
<br/>dif(cos(x), 1) === -sin(x)
<br/>Nothing different from the sin'(x) and cos'(x)
<br/>But when the second parameter is not 1, 
<br/>dif(sin(x), 0.5) === sin(x + pi/4)
<br/>dif(sin(x), 0.25) === sin(x + pi/8)
<br/>Now we have some basic tools to handle non-integer-time-differential. 

What's really interesting:
<br/>Fow now, we don't have a tool to figure out the partial differential for either x or y in dif(x*y, 0.123), but if we can do some reverse Taylor series expansion, I mean, if we can express polynomials with only trigonometric functions, then we can take all the advantages of trigonometric functions and the new trick we just got. In my new idea, maybe exponential function is better at this, since maybe it can do partial differential easier than trigonomitric functions.

I'm gonna wrap this doc up here. I don't have that much time. 

Have fun with this new idea.
