# C++ Practice

C++ exercises covering programming fundamentals, problem-solving, and object-oriented programming.

## Structure

- `basics/` — variables, input/output, loops, and conditions
- `functions/` — function examples
- `oop/` — classes and objects
- `data-structures/` — arrays, vectors, and linked lists
- `projects/` — larger programs

## Running a program

```sh
g++ basics/hello.cpp -o hello
./hello



### 2. Create `basics/hello.cpp`

Create a file named `basics/hello.cpp` and add:

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, C++!\n";
    return 0;
}