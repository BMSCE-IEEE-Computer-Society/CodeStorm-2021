# Prefix to Postfix

> Here is the srcambled code that converts a prefix expression to a postfix expression.

> If you don't know what a pre/postfix expression is check this out: [link](https://runestone.academy/runestone/books/published/pythonds/BasicDS/InfixPrefixandPostfixExpressions.html)

> **Unscramble it.**
> ```C 
> ||
> ```

> ```
> ,
> ```

> ```C 
> #include <stdio.h>
> ```

> ```C
> c==’+’
> ```

> ```C
> char c
> ```

> ```C
> c==’-’
> ```

> ```C
> main()
> ```

> ```C
> 0
> ```

> ```C
> putchar(c);
> ```

> ```C
> ||
>```

> ```C
> main()
> ```

> ```C 
> int main() {
> ```

> ```C 
> c==’*’
> ```

> ```C 
> c==’/’
> ```

> ```C 
> :
> ```

> ```C 
> ?
> ```

> ```C 
> getchar();
> ```

> ```C 
> }
> ```

> ```C
> ||
> ```

# Solution

```C

#include <stdio.h>

int main() {
    char c = getchar();
    (c == '+' || c == '-' || c == '*' || c == '/') ? main(), main() : 0;
    putchar(c);
}


```