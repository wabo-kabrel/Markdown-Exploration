# Code Blocks
## Inline Code  
Use `backticks` to highlight inline code.  
The `printf()` function is used for output.  

## Fence Code Blocks  
```
Basic code block without syntax highlighting  
```  
  
```python
def hello_world():
    print("Hello, World!")
```

```javascript
function greet(name) {
    return `Hello, ${name}!`;
}
```

```bash
npm install
git commit -m "Initial commit"
```

## Popular Language Identifiers  
python, py
javascript, js
java
c, cpp, c++
html
css
bash, shell
json
xml
sql
yaml, yml
dockerfile

## Code Block with Line Numbers (GitHub)  
```python {.line-numbers}
def factorial(n):
    if n <= 1:
        return 1
    return n * factorial(n - 1)
```