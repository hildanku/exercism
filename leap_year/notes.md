## About .h
* .h extension is used to declare variables, func, const, and type definition

```
bool leap_year(int year); // Function declaration (prototype)
```

```
#define Pi 3.14 // Macro
```

```
typedef struct {
    float width;
    float height;
} Square;
```

## About Macro
* Macros are instructions that tell the compiler to replace code before the program is compiled. So before the program is run, the macro performs a simple text replacement to modify the source code. This is done using a preprocessor, which runs before the actual compilation process.
### Resources
* https://stackoverflow.com/questions/30000871/what-is-the-difference-between-global-variables-and-define-in-c
* https://www.ibm.com/docs/en/zos/2.4.0?topic=directives-macro-definition#macro_def
### C
```
#define PI 3.14159

int main() {
    double radius = 5.0;
    double area = PI * radius * radius;
    return 0;
}
```
### PHP
```
define("PI", 3.14159);

$radius = 5.0;
$area = PI * $radius * $radius;
```