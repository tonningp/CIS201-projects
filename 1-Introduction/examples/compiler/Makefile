main: main.cpp
	g++ -o main main.cpp

run: main
	@./main

clean:
	@rm ./main ./main.s

assembly: 
	g++ -S main.cpp
	less main.s

edit: 
	vim main.cpp	
	

view: main.cpp
	less main.cpp

view-machine: main
	od -x main | less
