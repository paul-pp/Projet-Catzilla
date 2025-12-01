# Projet-Catzilla

This game has been developed in C++ from scratch using the SFML library.

## Requirements

To install and run the game, you must have:

- `g++` supporting at least **C++11**
- **SFML 2.6.1** (be careful, this is *not* the current version)

---

## 1. Install SFML 2.6.1

We recommend installing SFML from the source code available here:

    https://www.sfml-dev.org/download/sfml/2.6.1/

Place the source code in a directory that will not change (let's call it `$LIB_DIR`), then run the following commands in a Linux console (inside the SFML source folder):
mkdir build && cd build
cmake ..
make -j8
sudo make install

**Remark:**  
If you do not have CMake and you are on macOS, you can install it with: brew install cmake



---

## 2. Clone the project
git clone https://github.com/paul-pp/Projet-Catzilla


---

## 3. Compile the project
make


**Remark:**  
If errors occur here, there is probably an issue with SFML or its version.

---

## 4. Run Catzilla
./Catzilla


**Remark (macOS rpath issue):**  
If you encounter an rpath-related error at this step, you can fix it using: install_name_tool -add_rpath $LIB_DIR/SFML-2.6.1/build/lib ./Catzilla
Alternatively, you can try recompiling using **Makefile_2** and updating the RPATH (the first line of the file) to: $LIB_DIR/SFML-2.6.1/build/lib













