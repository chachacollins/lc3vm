'''
# initialize the build scripts
cmake -S . -B build -DCMAKE_BUILD_TYPE=Debug

# build or rebuild as often as needed
cmake --build build

# run the vm
./build/lc3sim /path/to/lc3-program.obj
'''
