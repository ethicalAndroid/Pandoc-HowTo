# How to Convert Markdown to Word

Goal goal goal

## Prerequisites

- A working installation of Pandoc
- A Markdown file to be converted

## Steps

1. Locate your Markdown file in your computer.
1. Right-click the last folder of the file path. _See figure 1._
    <figure>
    <img src="select-last.png" alt="Picture of the end of the file path.">
    <figcaption>Figure 1</figcaption>
    </figure>
1. Click the "Copy Address" option. _See figure 2._
    <figure>
    <img src="copy-address.png" alt="Picture of the end of the file path.">
    <figcaption>Figure 1</figcaption>
    </figure>
1. Open the command prompt.  
    > Tip: The command prompt can easily be found by searching it using the "search" tool in the taskbar of any Windows machine.
1. Type `cd Z` into the prompt.
1. Replace `Z` by pasteing the file path using CTRL-V.
1. Press the ENTER key.
1. Type `pandoc -f markdown -o output.docx Z` into the prompt.
1. Replace `Z` with the name of your markdown file.
    > Tip: Make sure you type the `.md` markdown file extension.  
    > Tip: If your markdown file name has spaces in the name, surround it in quotation marks like this, `"example of spaces.md"`.  
    > Tip: You can also replace `output` with any name you want.
1. Press the ENTER key.

## Results

You should have a Word file with the `.docx` file extension.  
Make sure to examine your file for any errors in the conversion.
