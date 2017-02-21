# Installation

1. install joystick driver from:
https://github.com/360Controller/360Controller/releases

2. connect joystick:
https://www.tweaking4all.com/os-tips-and-tricks/macosx-tips-and-tricks/xbox-360-controller-on-mac/

3. install deps

```
brew install sdl2
```

4. compile

```
cd build
cmake ..
make -j4
```