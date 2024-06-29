# CPSC471_ProgAssign

Jong Kevin Kim <br>
Email: jkim3442@csu.fullerton.edu

Anthony Ortiz <br>
Email: anthonyortiz7575@csu.fullerton.edu

Audrey Hsu <br>
Email: ahsu016@csu.fullerton.edu

Mark Raden
Email: mraden@csu.fullerton.edu

Kiet Nguyen
Email: kylekiet@csu.fullerton.edu

## Programming Language(s)

Python

## How to Execute Program

First you have to run the server side code. To do this in one terminal you can run:

```bash
python sendfileserv.py 21
```

Afterwards you then can run the client side code. To do this you can do this in another terminal with:

```bash
python sendfilecli.py 21
```

Once both are started up and connected you should be prompted with

```bash
'Enter command (ls, get<file>, put<file>, quit): '
```

### ls

Entering 'ls' will display the contents of the directory

### get \<file>

Entering get \<file> will have the server send the server the requested file and will show you if the file is successfully recieved and the amount of bytes recieved.

### put \<file>

Entering put \<file> will have the client send the server the requested file and will show you if the file is successfully recieved and the amount of bytes recieved.

### quit

Entering 'quit' will exit you from the program disconnect you from the socket.

## Notes

Only certain combinations work at this moment. Below are the working combinations:

get file.txt-> put file.txt
put file.txt
ls -> put file.txt
