# RISC OS uCLib (Micro C Library)

This is a simple and really small C Library to be used when creating Utils in C. 

The library is written partially in ARM Assembly (AArch32) and partially in ANSI C (C99) and it's for static link use only at the moment.

## Build the lib
To build from the source just git clone this repo and then go to uCLib -> src directory.

## Building using ROOL DDE
Before you try to build the lib make sure your RISC OS Filer has "seen" the !SetPaths application inside the AcornC_C++ directory you created when you installed ROOL DDE.

To build the lib directly is very easy, just double click on the MkDDE script file you'll find in uCLib -> src.

The building process will copy the object files in !LibuCLib app in the right places and also the header files as required.

For Acorn/ROOL Builder users:
At this time building the lib using Builder is not supported, I'll have a look into that and make sure it can be built using the Builder too in the future.

## Building using GCC
At this time building using GCC is not yet supported, so please be patient, it will definitely be done as soon as the library gets useful enough.

## How to use the library
To understand the details of how to use it, please have a look at the test files in the "tests" directory.

In general terms the idea behind this library is to provide a minimal and functional set of C functions so that you can easily create utils that:
- Accept input parameters from the command line
- Can print out messages on the screen
- Can do file I/O
- Have basic C strings support (for text manipoulation)

If you believe there is a need for more than the above please open an appropriate issue using the "Issues" tab above.

## Feedback
Feedback is always welcome!

### In case of problems
For any issue you may encounter, please use the "Issues" option here on GitHub. You can find it at the top of the page. Please do not try to contact us directly, the RISC OS Community handles all the communications here on GitHub.

### Requesting new features
As for the problems reporting, please use the Issues option here on GitHub also to request new features.

### Contributing
We welcome improvements and new ideas, before you submit your changes please have a look at the Contributing Guidelines [here](./CONTRIBUTING.md)

## License
uCLib is copyright by Paolo Fabio Zaino and is distributed under Apache License 2.0, please read the license [here](./LICENSE) for details

## Contributors
[<img src="https://avatars2.githubusercontent.com/u/8824337?s=42&v=4" width="42" alt="Paolo">](https://github.com/pzaino)  - uCLib original author

[<img src="https://avatars2.githubusercontent.com/u/72400477?s=42&v=4" width="42" alt="InteractiveYelp">](https://github.com/InteractiveYelp)  - Code reviewer

[<img src="https://avatars2.githubusercontent.com/u/358614?s=42&v=4" width="42" alt="skymandr">](https://github.com/skymandr)  - Code reviewer

