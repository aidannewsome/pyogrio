vcpkg's GDAL 3.12.4 port (vcpkg 89dac9685f), with one patch for Maquette's wheels: the FileGDB spatial index of a
layer in a Mercator CRS clamps northings to 0 with PROJ 9.7.1 and later, so box reads through it miss features.
