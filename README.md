First, write the your file path in the first textbox.
Then, press Enter or ctrl-g to focus the text area.
Press ctrl-g to save your file. Sadly the program will reset
Open your new file in an editor of your choice.

There are some useful commands, write them on the last line.
line1number @copyto line2number: copy line1 content to line2.
*before*
1- Python is good
2- C is better
3- 1 @copyto 2
*after*
1- Python is good
2- Python is good



line1number @swap line2number: swap line1 content with line2.
*before*
1- Python is good
2- C is better
3- 1 @swap 2
*after*
1- C is better
2- Python is good

@remove line1number: remove line
*before*
1- Python is good
2- C is better
3- @remove 2
*after*
1- Python is good

*Changes effective in the file created*
@run: run the program in a new terminal window, based on his file extension
*only py,js,rb,php*


@quit: interrupt the program





