Readme for Python 3 compatible Version
Author: Nila Mandal

An edit of the original vasp2cif, which was in Python 2. This version is
compatible with Python 3.


Changes made:
1. replaced Python 2 "commands" module with Python 3 "subprocess" module.
2. Changed file-reading method from Python 2 "file()" to Python 3 "open()"
3. Changed line "coords = map(float,poscar[i+offset+1].split()[0:3])" to
  "coords = list(float(x) for x in poscar[i+offset+1].split()[0:3])"" to
  support indexing.
4. Updated revision history.  

Use installation instructions from the original README.md to install.
