kwsrepl
=======

kdb+/k/q live REPL over web sockets.

![](demo.gif)

Dependencies
------------
- [kdb+/k/q](http://kx.com/software-download.php)

To run
------
1. Drop the html/ folder and kwsrepl.q in the q directory.

2. Start the kdb+/k/q web socket server:
	Linux: /path/to/q/l32/q kwsrepl.q -p 80
	Windows: /path/to/q/w32/q kwsrepl.q -p 80

3. Browse to http://localhost/kwsrepl.htm
