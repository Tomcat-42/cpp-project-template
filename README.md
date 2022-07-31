# cpp-project-template

A small/medium c++ project template using ```make``` as builder and ```doxygen``` for documentation.

## docs

The ```Doxyfile``` file holds *doxygen* parameters.

Documentation will be saved in the ```doc/``` dir , and a optional project logo must be in the file ```assets/logo.png```.

Use the following target for building documentation.

```bash
make docs
```

## Targets

```bash
# default is release
make

# Running the target
make run

# all
make all

# explicitly realese
make release

# Test
make test

# Debug
make debug

# clean
make clean
```
