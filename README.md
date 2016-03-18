# itoa_ljust
Fast and simple integer to ASCII conversion:
  * 32 and 64-bit integers
  * signed and unsigned
  * user supplied buffer must be large enough for all decimal digits in value plus minus sign if negative
  * left-justified
  * NUL terminated
  * return value is pointer to NUL terminator

Files:
  * itoa_ljust.h   - programming interface
  * itoa_ljust.cpp - implementation - compile and link with your application

```c++
char* itoa(uint32_t u, char* buffer);
char* itoa( int32_t i, char* buffer);
char* itoa(uint64_t u, char* buffer);
char* itoa( int64_t i, char* buffer);
```
