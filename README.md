# SystemC

SystemC Open Source Implementation Clone from 
[Accellera.org][1]

## Project Structure

Following directories contains:

* __[systemc](systemc):__ Contains the base source code of the SystemC Standard Open Source
  Implementation.
* __[systemc-regressions](systemc-regressions):__ Contains the regressions test suite for the above
  mentioned library.

___

**Note:**
1. Only Releases from `2.3.1a` and later are archived here, due to 
   re-licensing of the SystemC Standards Open Source Simulator Implementation.
2. Kindly follow the `dev` branch for fixes or enhancements, since `master`
   branch would be tracked with releases from [Accellera.org][1].

[1]: http://accellera.org/downloads/standards/systemc

___

## To-Do

1. Add support for `pkg-config` file generation in `CMake`.
2. Add C++ standard compilation flag in `configure` build script. Due to
   frequent mismatch between different project compilation flags options.

