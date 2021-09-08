# STEPin-Matrix_Calculator

[![codeQualityscore](https://www.code-inspector.com/project/28126/score/svg)](https://frontend.code-inspector.com/public/project/28126/STEPin-Matrix_Calculator/dashboard)
[![codegrade](https://www.code-inspector.com/project/28126/status/svg)](https://frontend.code-inspector.com/public/project/28126/STEPin-Matrix_Calculator/dashboard)
[![C/C++ CI - Build Status](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/c-cpp.yml)
[![Code Quality - Static Code - Cppcheck](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/cppcheck.yml)
[![Unit Testing - Unity](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/unity.yml/badge.svg)](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/unity.yml)
[![Valgrind](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/vidyasrik/STEPin-Matrix_Calculator/actions/workflows/Valgrind.yml)



# Challenges Faced and How Was It Overcome

| No. | Challenge | Solution
|-----|-----------|--------
|1. | Dynamic memory allocation of 2D arrays created segmentation faults| running the code in GDB helped find the line where the program crashes
|2. | Program crashes | Writing clean code with allocating and deallocating memory at all functions as per requirement|
|3. | Logical errors faced while designing matrix operations| Referred some articles to revise matrix basics and operations on 2D arrays
|4. | Unit testing on dynamic 2D array outputs| Created enumerated variables to be returned by those functions if the specified operation executes successfully
