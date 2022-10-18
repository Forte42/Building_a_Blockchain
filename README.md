# Building_a_Blockchain

In this code I create a simple proof of work function with a blockchain explorer and validation function. I then use streamlit to interact with the blockchain.

---

## Technologies

This code was written on Windows 11 running python 3.8.13. It also uses Pandas (Version 1.3.5) and Streamlit (Version 1.13.0).

---

## Installation Guide

All required packages can be installed with pip install.

---

## Usage

To interact with this code install Streamlit, open your command line, and navigate to the folder containing "pychain.py". Once there run the file in streamlit by typing "streamlit run pychain.py". Your web browser will open and display the following streamlit page:

![streamlit_screenshot.](images/streamlit_screenshot.png)


You can then create a block containg the receiver, sender, and ammount of the transaction. The widget at the bottom of the chain can be used to scroll through the block chain and the "Validate chain" button will run through the whoole chain and verify that each block's hash is the same as the next block's "Prev hash". If it is the page will show "True".

While running the app, you can watch your terminal to see the "winning hash" when the proof of work function finds a valid hash. It should look something like this:

![command_line_screenshot.](images/command_line_screenshot.png)
---

## Contributors

Garrett Hernandez -gtkhhz@gmail.com

---

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <https://unlicense.org>