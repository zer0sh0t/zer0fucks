zer0fucks is a lightweight, super fast [brainfuck][https://en.wikipedia.org/wiki/Brainfuck#:~:text=Brainfuck%20is%20an%20esoteric%20programming%20language%20created%20in%201993%20by%20Urban%20M%C3%BCller.&text=Brainfuck%20simply%20requires%20one%20to,the%20limits%20of%20one%27s%20understanding.] compiler

compile the source code and grab the executable:

    gcc zer0fucks.c -o zf.out

then, you can use this executable file to compile brainfuck programs. to get only the output of a brainfuck program:

    zf.out <input_brainfuck_file_name>

to get the output along with the interpreted(and properly formatted) c file:

    zf.out <input_brainfuck_file_name> <output_c_file_name>

you need [the ascii table](https://www.cs.cmu.edu/~pattis/15-1XX/common/handouts/ascii.html) to program in brainfuck
