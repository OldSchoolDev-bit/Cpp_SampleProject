This project template contains the boilerplate code for a C++ project. It is configured to work with GCC, Clang, and MSVC compilers.

## Directory Structure

- `src/`: Contains the source code for the project.
- `build/`: Target directory for the compilation process and generated output files.

## Compiler Support

The project template supports the following compilers:

- GCC: GNU Compiler Collection (MinGW-W64)
- Clang: LLVM Compiler (MinGW-W64)
- MSVC: Microsoft Visual C++ Compiler

## Building and Running

To compile the project, follow these steps:

### GCC

1. Make sure GCC compiler is installed.
2. Navigate to the root directory of the project.
3. Run the command `g++ -std=c++20 -o build/rooster.exe src/*.cpp`.

### Clang

1. Make sure Clang compiler is installed.
2. Navigate to the root directory of the project.
3. Run the command `clang++ -std=c++20 -o build/rooster.exe src/*.cpp`.

### MSVC

1. Make sure MSVC compiler is installed.
2. Navigate to the root directory of the project.
3. Run the command `cl.exe /Zi /std:c++latest /EHsc /Fe:build\rooster.exe src\*.cpp`.

## Running the Project

Once the project is successfully compiled, you can run it by using the generated output file. Navigate to the `build` directory and execute the `rooster.exe` file.

## Customizing the Project

You can customize the boilerplate code as per your requirements by adding your own functions and classes. Add new header and source files and update the compilation commands in the `tasks.json` file to include the new files.

## Troubleshooting

- If you encounter any issues with compilation or execution, ensure that the required compilers are correctly installed and included in your system's path variables.
- Also, check the configuration in the `tasks.json` file to ensure that the paths and compiler options are correctly specified.

For any further questions or issues, feel free to reach out to us.

Happy coding!
