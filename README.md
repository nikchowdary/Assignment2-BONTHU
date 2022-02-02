# Assignment2-BONTHU
Create for Assignment 2

# Nikhilchowdary Bonthu
###### Kfc America
Kfc located beside the famous **Hanger theater** and it's also have a **drive through** option so we can esaily pick food and  eat while driving
***
# Travel
### Vijayawada aitrpot is nearest to the cross road resturant.

1. Airport is very far from the city.
2. When you come out from the airport we go exactely 15kilometers towards to the south direction then we can seen a junction
3. From that junction we go 2 kilometers towards north direction then we can seen a famous Crossroads resutarant.

* Briyani
* Chilly chicken
* Apollo fish

[About Me](https://github.com/nikchowdary/Assignment2-BONTHU/blob/4277209093fb3d4230c7c595e1b5d51c56e19ef7/AboutMe.md)

***
### Sports avaible

Below are some sports i would recommend my friends

| Sports     | Venue       | Cost |
| --- | ----------- |  ----------- | 
| Cricket    | coldenhall  | 10$ |
| Badmantion | Zim center  | 20$ |
| Tabeltennis| library     | 25$ |
| Basketball | zim center  | 15$ |

****
>All is well - *Arayabata*


>Everbody is a genius  - *Newton*

***
### codfe fencing
> Dynamic programming is both a mathematical optimization method and a computer programming method. The method was developed by Richard Bellman in the 1950s and has found applications in numerous fields.<https://en.wikipedia.org/wiki/Dynamic_programming>

> Linear algebra is central to almost all areas of mathematics. For instance, linear algebra is fundamental in modern presentations of geometry, including for defining basic objects.<https://en.wikipedia.org/wiki/Linear_algebra> 

> In numerical analysis, a numerical method is a mathematical tool designed to solve numerical problems. The implementation of a numerical method with an appropriate convergence check in a programming language is called a numerical algorithm.<https://en.wikipedia.org/wiki/Numerical_method>

```
vector<int> z_function_trivial(string s) {
    int n = (int) s.length();
    vector<int> z(n);
    for (int i = 1; i < n; ++i)
        while (i + z[i] < n && s[z[i]] == s[i + z[i]])
            ++z[i];
    return z;
}
```
Here is the code source link <https://cp-algorithms.com/string/z-function.html>
