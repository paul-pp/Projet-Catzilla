# Projet-Catzilla

This game has been developed in C++ from scratch with the SFML library.

To install the game you must have :
- g++ to run at least C++ std 11
- SFML 2.6.1 (be carrefull, this is not the current version)

1. To install SFML 2.6.1 we recommend you to install the source code available here https://www.sfml-dev.org/download/sfml/2.6.1/
Then, put the src code in a directory you won't change (let's call it $LIB_DIR) and run the following lines in the linux console (inside the folder) :
$mkdir build && cd build
$cmake ..
$make -j8
$sudo make install

Remark : If you don't have cmake and you use Mac, you can run "brew install cmake" in order to install it.

2. Get the project from git :
$git clone https://github.com/paul-pp/Projet-Catzilla

3. Compile the project :
$make

Remark : if you have errors here, there is probably an issue with sfml or the version used

4. Run Catzilla :
$./Catzilla 


