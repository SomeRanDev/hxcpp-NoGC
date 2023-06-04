# hxcpp - No Garbage Collector Edition

See my project [Reflaxe/C++](https://github.com/RobertBorghese/reflaxe.CPP), which was the solution I came to eventually for solving GC in `Haxe -> C++` transpiling.

~~A version of hxcpp.h that makes Haxe/C++ output inherently use no gc, only value types. Simply swap out the normal hxcpp.h in your C++ with this file and it (should) work?~~

~~This exists as a solution for projects that need to be incorporated into C++ code bases with existing GC solutions, or for those that would rather rely on predicatable memory management. Works great with smart pointers as well. Since it simply converts everything into value types, it should theoretically not require any manual memory management, but may come at a performance cost if used incorrectly.~~

~~This project mainly exists to help with my [Haxe for Unreal Engine 5](https://github.com/RobertBorghese/Haxe-UnrealEngine5) project.~~
