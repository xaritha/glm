
# *OpenGL Mathematics for C*

[*glm-c*](https://github.com/sizeof-voidp/glm-c) is a C alternative of the C++ library [*glm*](https://github.com/g-truc/glm).
It was made referencing the [*GLSL specification*](https://www.khronos.org/registry/OpenGL/specs/gl/GLSLangSpec.4.60.pdf) as well. This is meant to be used in C11+ (C11, C18, C2x, etc...), you could use this no problem in earlier standards with a smaller feature set.

### Features

- [x] All 38 *GLSL* types, and their related functions.
- [x] Exact *GLSL* constructor syntax.
- [x] Exact *GLSL* internal function syntax.
- [x] Zero cost swizzling for contiguous combinations of elements. (i.e. xy, gb)
- [x] All 20 *GLSL* vector types.
- [x] All 18 *GLSL* matrix types.
- [ ] Camera helper functions.
- [ ] Quaternions.
- [x] Static asserts for valid code generation.
- [ ] Inline code generated by macros for all types. (Manually write expanded code into the C files)
- [ ] Swizzling functionality.
- [ ] *FMV* (Function Multi-Versioning) system for run-time optimization.
- [ ] Manually optimize versions of common vector or matrix operations using inline assembly. (Intel SSE, Arm NEON, etc..)
- [ ] Ability to build *glm-c* as a shared or a static library.
- [ ] Custom format printing function.
