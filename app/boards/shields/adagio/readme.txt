cd app
west build -d build/left -p -b nice_nano -- -DSHIELD=adagio_left
west build -d build/right -p -b nice_nano -- -DSHIELD=adagio_right