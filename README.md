# text-util

A console text utility that is sort of plugin based.
You can even make your own plugins for it, atleast that's the idea.

The project is a way for me to experiment with shared libraries and modular polymorphism (not even sure if this is a thing people say but seems like a nice fit).

The core idea is: A text utility tool that you can tell it what plugins to use to modity some text you pass it. The plugins are in the form of shared libraries that you can even make yourself. I hope that in the end it becomes a usefull thingy and maybe even have a default configuration that you can set to... well have default plugins or something. Written in C++ because it's a nice language if you are looking for a challenge.

MIT license because I believe it's a nice license for this kind of project. Feel free to try it out, beware that the branch might be broken and cross-platform compatibility is not yet a concern. Compiled using Clang++ 15 most likely, and the code here will mostly target a 64 bit arm machine, running a branch of Debian.
