# conan-stb

[![Download](https://api.bintray.com/packages/conan-community/conan/stb%3Aconan/images/download.svg?version=1.1.5%3Astable)](https://bintray.com/conan-community/conan/stb%3Aconan/1.1.5%3Astable/link)
[![Build Status](https://travis-ci.org/conan-community/conan-stb.svg?branch=release%2F20180214)](https://travis-ci.org/conan-community/conan-stb)

[Conan](https://conan.io) package for [stb](https://github.com/nothings/stb).

The packages generated with this *conanfile.py* can be found in [Bintray](https://bintray.com/conan-community/conan/stb%3Aconan).

## Basic setup

    $ conan install stb/20180214@conan/stable

## Project setup

If you handle multiple dependencies in your project is better to add a *conanfile.txt*:

    [requires]
    stb/20180214@conan/stable

    [generators]
    cmake

    
## License

Current repo is [MIT License](LICENSE)
Check the specific license for the library being packaged.