all:
	g++ -std=c++11 -c -g  app.cpp game.cpp plane.cpp menu.cpp -I./Box2D

compile:
	g++ app.o game.o plane.o menu.o -L./Box2D/Build/bin/x86_64/Debug -lBox2D -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio

clean:
	$(RM) compile*.o*~
