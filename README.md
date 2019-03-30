# glad

Automatic generation with cmake of the openGL Loaders based on the official specs using the
[https://github.com/Dav1dde/glad] package


### Usage

```
set(GL_CORE_VERSION         3.3 CACHE STRING "" FORCE)
add_subdirectory(glad)
```

### Notes
Currently `GL_CORE_VERSION` variable is not working, will generate the latest available version
