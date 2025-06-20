# Template for SFML3 Steam application in `cppfront`

## Setup
- Get [`cppfront`](https://github.com/hsutter/cppfront) and build the compiler ([docs](https://hsutter.github.io/cppfront/welcome/overview/))
- Get [`SFML3`](https://www.sfml-dev.org/download/sfml/3.0.0/)
- Get [`Steamworks SDK`](https://partner.steamgames.com/?goto=%2Fdownloads%2Flist)
- Add `cppfront`(`.exe`) directory to path
- In Visual Studio, add user macros to `LocalIncludes.prop`
  - This is accessible in the `View → Other Windows → Property Manager` pane under any specific configuration (i.e. `Debug | x64 → LocalIncludes` -- they are all references to the same prop)
    - `cppfront` (i.e. `C:\github\cppfront`)
    - `SFML` (i.e. `C:\SFML-3.0.0`)
    - `steamworks` (i.e. `C:\steamworks_sdk_162`)
