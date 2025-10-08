# Amy-client-intern
A small example C++ client project managed with CMake. It includes an example src/main.cpp and the header-only nlohmann/json library (include/nlohmann/json.hpp).

Features
CMake-based build
Example CLI program
Header-only JSON (nlohmann/json) included in include/
Repository structure
CMakeLists.txt
include/nlohmann/json.hpp
src/main.cpp
README.md
Prerequisites
CMake >= 3.10
A C++ compiler supporting C++17:
Windows: Visual Studio (C++ workload) or MinGW/MinGW-w64
Linux/macOS: gcc or clang
Build and run (example)
Create build directory and enter it:
mkdir -p build
cd build

Generate build files and build:

Visual Studio (Windows): cmake .. cmake --build . --config Release
MinGW (Windows, Git Bash): cmake -G "MinGW Makefiles" .. mingw32-make
Linux / macOS: cmake .. make
Run the produced executable (name may vary, e.g. todo or todo.exe):
./todo.exe    # Windows
./todo        # Linux/macOS

Common troubleshooting
"No CMAKE_CXX_COMPILER": install Visual Studio C++ tools or MinGW, or ensure compiler is in PATH.
LF/CRLF warnings on Windows: git config --global core.autocrlf true
Contributing
Create a branch for new work: git checkout -b feature/your-feature
Commit and push the branch, then open a Pull Request on GitHub.
License
Add a LICENSE file if needed (e.g. MIT).