1. [Header 1](#header-1)
   * [Header 1.1](#header-1.1)
     * [Header 1.1.1](#header-1.1.1)
     * [Header 1.1.1](#header-1.1.1)
     * [Header 1.1.1](#header-1.1.1)
2. [Header 2](#header-2)
   * [Header 2.1](#header-2.1)

## Header 1

text

### Header 1.1

`code`

```python
import numpy as np
def fibonacci(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)
def fib(n):
    return np.array([fibonacci(i) for i in range(n)])
```

```javascript
const person = {
  name: ['Bob', 'Smith'],
  age: 33,
  gender: 'male',
  interests: ['music', 'skiing'],
  bio: function() {
    alert(this.name[0] + ' ' + this.name[1] + ' is ' + this.age + ' years.');
  },
  greeting: function() {
    console.log('Hi! I\'m ' + this.name[0] + '.');
  }
};
function person_dbg(p){ 
  console.log(` --- p.age: ${p.age}`);
  console.log(` --- p.greeting(): ${p.greeting()}`);
}
```

```tex
$$\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$$
```

#### Header 1.1.1

**bold** *italic* ~strikethrough~

___italic bold___ and ***italic bold***

> blockquote

#### Header 1.1.1

- list item 1
- list item 2

#### Header 1.1.1

1. numbered list item 1
2. numbered list item 2

## Header 2

text

### Header 2.1


Before

|h|Long header|
|-|-|
|abc|def|
|abc2|def2|

After

| h    | Long header |
 |------|-------------|
 | abc  | def         |
 | abc2 | def2        |
