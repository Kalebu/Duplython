# Duplython

What is Duplython ?
-------------------

Duplython is a simple cli app that can be used to recursively remove duplicates files over a given directory using Python


How does it work ?
--------------------
Duplython underhood is able to detect any duplicate file using **hashing**, each single file whether its image | music | video has a unique hash, so if any two file with duplicate hash, one of them will be removed.


Getting started 
------------------
To start using this tool you might wanna clone or download this repository 

```bash
$-> git clone https://github.com/Kalebu/Duplython
```

Dependencies 
-------------

You don't need to install anything, all the libraries and module used in this tool are found in the Python standard library.


Move into project directory
---------------------------

Now move into the project repository and you will see a script named **app.py** , now move it to the top directory of a folder you would to clean up the duplicates, whether its your music folder , video folder, or disk top directory and then run the script.

```bash
$-> python app.py
```

Duplicates Screaming out
--------------------------
Now once you run the script, the duplicates present in any subfolder of a top directory will be screaming out as a result of script detecting them thus removing their finger print to your disk, adding up more space to store your important files

Issues 
-----------

Incase you have any difficulties or issues while trying to run the script
you can raise it on the issues. 

Pull Requests
----------------

If you have something to add I welcome pull requests on improvement , you're helpful contribution will be merged as soon as possible 

Give it a Star ✴️
--------------------
If you find this repo useful , give it a star

Credits
-----------
All the credits to [kalebu](github.com/kalebu)
