
```bash
patch -p0 < netcdf.patch
./configure --enable-static --disable-shared --prefix=.../W64soft/ --build=x86_64-w64-mingw32  --disable-netcdf-4 --disable-dap &&\
  make &&\
  make install
```

```bash
patch -p0 < netcdf.patch
./configure --enable-static --disable-shared --prefix=.../W32soft/ --build=i686-w64-mingw32  --disable-netcdf-4 --disable-dap && \
  make && \
  make install
```
