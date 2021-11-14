# smallest-pong
My try at making the smallest pong i could in C++

The code is horrible and its really undreadable i know but its also very small (around 10KB)
It also only works for **Linux** because i used X11

it also flickers and glitches sometimes but overally it works
You start game by pressing Space and the game is for two players (Up and Down, W and S)

# Compile
idk why would you like to compile it but bascially just compile with
  `g++ pong.cpp -o pong -O2 -lX11`
then to make it smaller you can
  `strip pong`
and at the end to make it even smaller i used upx to compress the binary
  `upx pong` (can use -9 or -lzma)
