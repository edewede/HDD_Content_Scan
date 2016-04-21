## Synopsis

This shell scripts quickly identify the contents of a large harddrive (with tree structure) and then emails users with a shortened directory list while also attaching a full file list as an excel sheet.


## Motivation

While working in an large film archive I kept getting requests for content logs of harddrives. So I wrote this script to quickly enter the Name of the title, it's library barcode, and then output the contents directly to the requester's email. Saved me a bunch of time. 

## Installation

I install most of my tools via brew: 

brew install tree (This installs the tree directory tool)  
brew install mutt (This installs the email client)  
install ssconvert. (Instructions here: http://www.linuxfromscratch.org/blfs/view/7.9/xsoft/gnumeric.html //to convert output from tree command to an excel spreadsheet.)

## License

MIT License

Copyright (c) [2015] [Javier Kadry]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
