main: main.cpp
	g++ -o main main.cpp

run: main
	@./main

edit:
	@vim main.cpp

clean:
	@rm ./main

assembly: 
	g++ -S main.cpp
	less main.s

view: main.cpp
	less main.cpp

view-machine: main
	od -x main | less
