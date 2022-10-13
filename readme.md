# Valgrind Execise

## run files
mkdir build
cd build
cmake ..
make
Run tests: ./test/cpp-test
Run program: ./app/shell-app

## Run valgrind to check error

valgrind —leak-check=full ./app/shell-app

## Run Kcachegrind to check

valgrind --tool=callgrind ./app/shell-app
