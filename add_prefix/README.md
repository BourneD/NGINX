1) ./configure --add-module=path/to/add_prefix
2) make
3) sudo make install
4) nginx.conf: add "add_prefix on;" in http{}
5) prepare hello.txt in location root directory
