DefMiner   v1.0.0 - 2013-12-17
Automatic Definition Extraction System
-----------------------------

Copyright (c) 2013-2014 Web Information Retrieval/Natural
Language Processing Group at National University of Singapore

Author: Yiping Jin

The system is based on Yiping's thesis and EMNLP paper. Please
refer to:

http://wing.comp.nus.edu.sg/downloads/term_definition_mining/

DOCUMENTATION

LICENSE

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA.

For more information, bug reports, fixes, contact:
    Yiping Jin
    Dept of Computer Science,
    National Univeristy of Singapore
    Singapore

---------------------------------
Notice
---------------------------------
The software is currently not available on GitHub.
Please contact the author if you wish to obtain a 
copy of the software for research use. 

---------------------------------
Software Dependencies
---------------------------------
The software requires Python 2.7.X be installed. It 
might not work for version 3+ due to minor difference
in the syntax. It also requires JRE and C++ compiler 
to be installed.

The software can build without problem on a freshly 
installed Ubuntu 12.0.4 system. 

---------------------------------
Compilation
---------------------------------
Step 1: Compile CRF++
Below are the steps from their website:
(Note it may not work if you are not root user)

    - Go to CRF++-0.58/ sub-dirctory

    % ./configure 

    % make

    % su

    # make install

This project is developed mainly in Python and Java.
The code is portable and does not require further 
compilation.

---------------------------------
Run the Program
---------------------------------

To run the program from command line:

  .DefMiner_clean [input file]

To run from web CGI:

go to directory 

  defminer/CGI/webapp/

run command:

  python simple_httpd.py

then use the browser to open url:

  localhost:8080

---------------------------------
CHANGES
---------------------------------
2013-12-17      1.0     Initial release
