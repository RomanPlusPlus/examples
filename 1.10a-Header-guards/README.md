# 1.10a-Header-guards
solution for the quiz of this chapter:  http://www.learncpp.com/cpp-tutorial/1-10a-header-guards/

Header guards are designed to ensure that the contents of a given header file are not copied more than once into any single file, in order to prevent duplicate definitions. Note that header guards do not prevent the contents of a header file from being copied (once) into different project files. This is a good thing, because we often need to reference the contents of a given header from different project files.
