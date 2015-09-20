# Malware
A sample of malware from a variety of sources. 
[![Project Status](https://stillmaintained.com/ArcanaMagus/Malware.png)]
(https://stillmaintained.com/ArcanaMagus/Malware)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)]
(https://github.com/ArcanaMagus/Malware/blob/Malware/LICENSE)
[![Build Status](https://travis-ci.org/ArcanaMagus/Malware.svg)](https://travis-ci.org/ArcanaMagus/Malware)
[![Coverage Status](https://coveralls.io/repos/ArcanaMagus/Malware/badge.svg?branch=malware&service=github)](https://coveralls.io/github/ArcanaMagus/Malware?branch=malware)

/*---------------------------------------------------------

The included apps fx_infect and Malware inclusively are released as Open Source Software
And are subject to the MIT Software License Copyright (C) ArcWare Technology.
Attached to this Application or  at (least) one of its subclassed programs should
be a copy of the LICENSE File. Refer to file LICENSE for more details.

------------------------------------------------------------*/

  Note
======

All examples in this resource will be commented and command line interpreter (CLI) examples
Will appear as the following:
      
      >>>

The above demotes a Python interactive Shell command. That means that each can be run
dynamically from python bash, as well as be statically typed.
      
      #

The above denotes a commented line. therefore with the included 'hash'(#) character will 
be ignored by the interpreter.
  
  Installation
==============  

      pip install Malware
      
  Usage
========

Import and Initialization
  
    from malware import Malware
    ml - Malware()
    
Get Particular Process Id( i.e. Process ID on Malware Online)    

    pid = ml.get_pid('png')
    # >>> pid.process_id
    # png
    # >>> pid.Arkana
    # 654747
      
Updates, Attacks, Logs, Call Tree info are similar to objects thus
they can be called by object/process id. To get data on an object by id.

    object = ml.get_object(8&6!)
    # >>> object.title
    # 'Example App: VisualStudio : lorem ipsum"
    # >>> object.type
    # update
    # >>> object.child
    # [ $1024, $1025, $1026, $1027, ...]
    
To get object ids for current top updates
    
    top_update_ids = ml.top_updates()
    # >>> top_update_ids
    # [ $6324785, $6324786, $6324787, ...]
    
To get current greatest size (object id):

    max_object = ml.get_max_object()
    # >>> max_object
    # $789652
        
## Offensive Exploits
The application can be launched using the command
<code>Malware.py</code> or similar, in the directory
 to which it was downloaded.
**Example** 
            <code>&/$Path_to\& == $PATH = <path></code>
            <code>./$PATH/Malware.py</code>
            
            *Note*
For each <path>path</path> element replace with your local download
```PHP
$PATH
```
### What this project contains
The software applications Malware and fx_infect inclusively, the latter being a
self-contained testing version of the former. 

####Usage(Advanced)
To invoke the package malware.py use a source control program (to contain 
the code safely). The program can be initialized suing the standarn notation,
Actually including the desired package (i.e. fx_infext.py, Malware.py) in a
method or class will allow much faster loading.

  ```python
def __Malware(package, contained, reference, buf_size=64 * 1920 * 1080:
    package.<effect> = Class
    package.downloaded = Class
    package.buffer = b'': bytes(bytes in parseError)
    package.buf_size = buf_size
    package.ref_element = ref_element
    """
    Replace the <Class> element with the name of the class the package is 
    loaded into.
    
    EXAMPLE: for class name : Sync_all 
    put (Sync_all) {
      for (element[sync] : len=all )
      }
      len = length.element(Node, Sync);
    """
```

