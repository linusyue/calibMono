### Compilation

Compile all the files using the following commands.

```bash
mkdir build && cd build
cmake ..
make
```

Make sure your are in the `build` folder to run the executables.

### Running
```bash
./calibMono -w=9 -h=6 -s=0.02423 -o=camera.yml -op -oe -su imagelist.xml

results saved in camera.yml
