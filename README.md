compile the source code and grab the executable:

    gcc zer0fucks/core.c -o zf.out

then, you can use this executable file to compile brainfuck programs. to get only the output of a brainfuck program:

    zf.out <input_brainfuck_file_name>

to get the output along with the interpreted(and properly formatted) c file:

    zf.out <input_brainfuck_file_name> <output_c_file_name>
