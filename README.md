# Little-cuda-sample

Learning CUDA sample step by step. This project demonstrates various CUDA programming techniques and optimizations.

## Project Structure

```
/workspace/
├── CMakeLists.txt          # Main CMake build configuration
├── LICENSE                 # Project license information
├── README.md               # This file
├── include/                # Header files
│   └── my_project.h
├── lib/                    # Library source files
│   ├── CMakeLists.txt
│   ├── my_lib.cpp
│   └── my_lib_impl.h
├── src/                    # Main source code
│   └── main/
├── test/                   # Test files and executables
    ├── makefile
    ├── run.sh              # Test execution script
    ├── test                # Test executable
    ├── test_device.cu      # CUDA device test code
    ├── test_device.o       # Compiled CUDA object
    ├── test_host.cpp       # Host-side test code
    └── test_host.o         # Compiled host object
```

## Features

- CUDA device programming samples
- GPU reduction optimization techniques
- Modular code structure with separate library and test components
- CMake build system integration
- Host and device code examples

## Build Instructions

This project uses CMake for building. To build the project:

1. Create a build directory:
   ```bash
   mkdir build && cd build
   ```

2. Configure the project:
   ```bash
   cmake ..
   ```

3. Build the project:
   ```bash
   make
   ```

## Testing

To run tests, you can use the provided test script in the test directory:
```bash
cd test
./run.sh
```

## License

This project is licensed under the terms found in the LICENSE file.

## Update Log

### 2024/08/21 - Test dev branch
Test dev branch, it includes a baseline about GPU reduce optimization.
