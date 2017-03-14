# python-cobra
Automatically exported from code.google.com/p/python-cobra
The visualization of the Python virtual machine, the purpose of the Python virtual machine in the implementation of a bytecode instruction 
when the runtime environment of the virtual machine state and displayed in visual form, in a more vivid way to deepen the readers 
understanding of Python virtual machine.

Contains two parts: 1, cobraserver: Python is the virtual machine modified 2, cobraweb: This is based on the visual interface of Django and
Ajax to compile cobraserver, you'll get a cobra-vm-server.exe, this is the server, start, and then in the cobraweb runserver can execute
manage.py, through the web communication interface and virtual machine the end, visualization of Python virtual machine. It should be 
noted that, at present, only the Windows platform cobraserver network code, so currently only run on the Windows platform. At the same time,
Web front-end browser is best to use FF2, IE is no problem, but the appearance may not be enough, FF3 changed the upload file input value 
of value, so the current FF3 can not operate properly.
