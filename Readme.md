## LibSSH Dash docset generator

Libssh dash docset generator generates docset for libssh library. If you want to have docset with
correct libssh logo in docset. Copy img/logo.png to output/html/org.libssh.docset/icon.png and add 
it to Dash.app.

### Building Dash docset

On Mac OS X you can build docset with these simple commands. On other systems docsetutils should
be installed.

```  bash
doxygen Doxyfile
cd output/html
make 
cp -r org.libssh.docset ~/Desktop/
```
