
add_numbers: add_numbers.cpp
	g++ add_numbers.cpp -o add_numbers
dump: add_numbers
	objdump -d add_numbers > add_numbers.asm
clean:
	rm -f add_numbers add_numbers.asm
run: add_numbers
	add_numbers