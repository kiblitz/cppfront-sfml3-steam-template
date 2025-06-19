# Template for SFML3 application in `cppfront`

## Setup
- Get [`cppfront`](https://github.com/hsutter/cppfront) and build the compiler ([docs](https://hsutter.github.io/cppfront/welcome/overview/))
- Add `cppfront`(`.exe`) directory to path
- In VS Studio
  - Add `cppfront/include` include directory to `LocalIncludes.prop`
    - This is accessible in the `View → Other Windows → Property Manager` pane under any specific configuration (i.e. `Debug | x64 → LocalIncludes` -- they are all references to the same prop)
    - `Common Properties → VC++ Directories → General → Include Directories`
