# elementals
Python package with basic utilities for CTF scripts (works well for exploit PoCs too).

## Install
```pip install elementals```

## Brief
The **elementals** python package is a utility package with handy tools for CTF scripts and PoC-style scripts. What was first implemented for personal use in small research scripts was now upgraded to be used by security researchers as a lightweight substitute to the famous pwntools package.

The features included in **elementals** are:
* **Logger:** Basic (logging based) logger - configured and ready to use 
* **Prompter:** Metasploit based stdout wrapper for the logger
* **ProgressBar:** User-friendly graphical progress bar
* **StatusBar:** User-friendly graphical status bar
* **createAnchor:** Creates a time-stamped output directory for all script outputs
* **hexDump:** Stylized hex dump for binary blobs / strings

Here is a screenshot from an example script with most of the features:
![alt text](https://github.com/eyalitki/elementals/blob/master/docs/elementals_poc.png "Full use case")
And here is an example of the hex dump output:
![alt text](https://github.com/eyalitki/elementals/blob/master/docs/elementals_hexdump.png "Hex dump")

## Used by
The **elementals** package is used in most of my scripts and also in my public Github projects:
* **Scout Debugger** - https://github.com/CheckPointSW/Scout
* **Karta (IDA Plugin)** - (soon to be released)

## References
* Twitter: [@EyalItkin](https://twitter.com/EyalItkin)
* E-mail: eyal dot itkin at gmail dot com
