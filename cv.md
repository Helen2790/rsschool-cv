# Helen Maruk
## Junior Frontend Developer
### Contact information:
**Phone:** +48 522 589 238
**E-mail:** maruk.lena27@gmail.com
**Telegram:** @soliaries
[LinkedIn](https://www.linkedin.com/in/%D0%B5%D0%BB%D0%B5%D0%BD%D0%B0-%D0%BC%D0%B0%D1%80%D1%83%D0%BA-a89658121/)
### About Myself:
I am an engineer by education. But I've always wanted to immerse myself in the world of programming. At school, I studied mathematics and physics in depth, so I always had a love for numbers and solving logical problems. Now I have studied the basics of frontend development and continue to dive into this topic. 
Since my hobby is photography, I know Photoshop well. I believe that frontend development combines both creativity and programming.
### Skills:
* HTML5, CSS3
* JavaScript
* Git, GitHub
* VS Code
* Adobe Photoshop
* Figma
### Code example:
A triangle is called an equable triangle if its area equals its perimeter. Return true, if it is an equable triangle, else return false. You will be provided with the length of sides of the triangle.

```javascript
function equableTriangle(a,b,c) {
  let pp = (a + b + c) / 2
  let s = Math.sqrt(pp * (pp - a) * (pp -b ) * (pp - c))
  return ((a + b + c) === s)
}
```