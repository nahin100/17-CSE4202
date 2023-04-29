win:
	g++.exe -fdiagnostics-color=always -I./include ./src/coordinate_systems_multiple.cpp ./src/glad.c -o ./build/main.exe -Llib -lglfw3 -lopengl32 -lgdi32
	./build/main.exe

linux:
	g++ -fdiagnostics-color=always -I./include ./src/shaders_class.cpp ./src/glad.c -o ./build/main -Llib -lglfw -lGL -lXrandr -lX11 -lrt -ldl
	./build/main