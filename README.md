# smart-forms

### Resources


[Evalutex.js](https://arthanzel.github.io/evaluatex/) can evaluate LaTeX formulas in Javascript

#### LaTeX Parsing

[jsMath](http://www.math.union.edu/~dpvc/jsMath/) can render LaTeX in Javascript
[MathJax](https://www.mathjax.org/) can also render LaTeX in Javascript, but it's much simpler to setup and doesn't require client-side resources to nominally work, unlike jsMath.

#### LaTeX Generating

[MathQuill](http://mathquill.com/) can help create LaTeX to be used

#### Docker Resources

Kicking off a local instance: 

```
sudo docker run -it -p 80:80 \
    -v /$PWD/web://usr/share/nginx/html:ro \
    nginx:alpine 
```


