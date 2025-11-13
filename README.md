# Your first Flipper Zero app

This project could be your first Flipper Zero app. There are many tutorials out there, the code in this repository is based on the first one:
* [Alan Gueret's blog](https://blog.gistre.epita.fr/posts/alan.gueret-2023-09-09-create_your_first_application_on_the_flipper_zero/) explains the code base [github.com/alanretgue](https://github.com/alanretgue/Flipper_Zero-app_tutorial)
* [Jacobie Barksdale's Youtube profile](https://www.youtube.com/@jblanked/videos) has many interesting videos on Flipper Zero apps, his code can be found at [github.com/jblanked](https://github.com/jblanked/Hello-World-Flipper-Zero)
* Of course, there is the [official development docu](https://developer.flipper.net/flipperzero/doxygen/).

## A simple 10 steps recipe
It is really much easier than you might expect, you just have to get started. The following steps should work on any operating system.
1. **Prerequisites.** Ensure that Phyton and GIT is installed on your system.
2. Download *uFBT*, the [**micro Flipper Build Tool**](https://github.com/flipperdevices/flipperzero-ufbt) with e.g. `python3 -m pip install --upgrade ufbt`.
3. Move to your Flipper Zero directory and clone the source code, e.g. `git clone --recursive https://github.com/fgreil/mitzi-hello-world`.
4. Make your changes using your favorite text editor.
5. Step into the directory `cd mitzi-hello-world`. The folder should contain at least the app manifest `application.fam` and your C source files. In our case, we also need a subfolder `mitzi-hello-world/images`.
6. Compile the app into a **Flipper Application Package** (file extension `*.fap`) with a simple `ufbt` in the command line. This may take a (short) while.
7. Debug, if the previous step showed warnings or errors. Go back to step 4.
8. Connect your Flipper Zero via USB and power it up. If it is already on and connected, make sure you exit all applications.
9. Launch your first app directly on the connected Flipper Zero with `ufbt launch`. This builds, uploads, and runs the app on your Flipper.
10. **READY.**

## Helpful resources
- Overview of different libraries [github.com/jamisonderek/flipper-zero-tutorials/(https://github.com/jamisonderek/flipper-zero-tutorials/wiki/Modules)
- [Visual guide to Flipper Zero GUI components](https://brodan.biz/blog/a-visual-guide-to-flipper-zero-gui-components/)
- Lewis Westbury's [Tutorial on Advanced Interfaces for Flipper Zero](https://instantiator.dev/post/flipper-zero-app-tutorial-02/) from 2023-05-05.
- https://github.com/flipperdevices/flipperzero-firmware/tree/dev/assets/icons is the offical Flipper Zero image collections, see e.g. the subfolder `Common`

## Who is Mitzi?
[Mitzi aka DRC-1958](https://cetacea.fandom.com/wiki/Mitzi_(DRC-1958)) was a female *Tursiops truncatus truncatus* who played the main character in the 1963 film "Flipper". Just another random fact for you.
