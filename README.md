# us_honeybee_prod
Want to view and clean the information on honeybees in the US and see how many registered Bee Colonys there are in Campbell County Kentucky? 

Setting Up the Program

1) First step is to go on GitHub  and clone the repo us_honeybee_prod into a gitbash terminal.

2) Next you want create a virtual environment in this directory using the command source venv/bin/activate or source venv/Scripts/activate.

3) Once the virtual environment is activated you want to use the command pip install pandas 

4) Open the file from my github repo for us_honeybee_prod titled Bee Colony Census Data by County KY2.xlsx. Now open it in Excell or jupyter notebook.

5) If in Excel Highlight the CV(%) column and delete then save to a new file named Bee Colony Census Data by County KY2clean.xlsx If in Jupyter notebook type " Import pandas as pd" 

6) Highlight and Delete the "Index" column then save to file Bee Colony Census Data by County KY2clean.xlsx

7) Highlight and Delete the "State" ANSI column then save to file Bee Colony Census Data by County KY2clean.xlsx

8) Highlight and Delete the "Period" column then save file to Bee Colony Census Data by County KY2clean.xlsx

9) Highlight and Delete all of the "2,002" in the years column then replace the cells with "2002".  Then save the file to Bee Colony Census Data by County KY2clean.xlsx.

10) Open the file Bee Colony Census Data by County KY2clean.xlsx now in Visual Studio Code and make sure to have the Excel viewer extension downloaded.
  
11) Open the file cleaned.py

12) Open the WSL or Gitbash terminal and ask the question " How many Beehives where in Campbell County Kentucky in 2002?"

13) The answer 151 should return in the terminal.

14) Make sure to run git pull then git push in the gitbash terminal to save the file to git hub.

15) Thank you for taking the time to check out this project that was done for a Data 1 Python course.  Thanks alot to Brenda Griffith too for providing the original raw data to start from.

Source
Brenda Griffith
https://data.world/siyeh
