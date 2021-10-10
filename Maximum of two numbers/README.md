# Maximum of Two Numbers

> **Unscramble this code that can find the maximum of two numbers.**

> Note: `___` is a placeholdder for any code or expression.
> ```
> #include <stdio.h>
> ```
> ```
> scanf("%d %d", &a, &b);
>```
> ```
> int main(){
> ```
> ```
> }
> ```
> ```
> printf("%d", ___)
> ```
> ```C
> int a, b;
> ```
> ```C
> int m = 
> ```
> ```C
> a+b
> ```
> ```
> /2
> ```
> ```
> +b
> ```
> ```
> sizeof(int)*8-1|1)
> ```
> ```
> (a-b)
> ```
> ```
> *(a-b))
> ```
> ```
> +(
> ```
> ```
> >>
> ```
> ```
> (___
> ```

# Solution

```C

#include <stdio.h>

int main() {
    int a, b;
    scanf(“%d %d”, &a, &b);
    int m = (a + b + ((a - b) >> sizeof(int) * 8 - 1 | 1) * (a - b)) / 2;
    printf(“%d”, m);
}


```