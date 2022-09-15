INSTRUCTIONS
–––––––––––––––––––––––––––
 - Please make sure java is installed and 'CookieCalcDownload' folder is on your computer's 'Downloads'
      - If the file is not in downloads it will not work properly
 - Also, an example sales file is provided to test the program

MAC
–––––––––––––––––––––––––––
 - Open terminal and paste the following:

chmod u+x /Downloads/CookieCalcDownload/CookieRun_Mac.command

 - 'CookieRun_Mac.command' can be moved anywhere
      - Could be placed on desktop
 - To start the program double click 'CookieRun_Mac.command'
 - If it does not run see Other (below)

Windows
–––––––––––––––––––––––––––
 - Try double clicking 'CookieRun_Windows.bat'
 - If it does not run see Other (below)
      - I do not have a Windows OS to test this on

Other
–––––––––––––––––––––––––––
 - Edit the following command where ** edit here ** appears
      - Remember to delete **

java -jar --module-path "**file path to javafx-sdk-18 > lib**" --add-modules javafx.controls,javafx.fxml "**file path to Cookie_Calculator.jar**"

 - DO NOT delete the quotation marks
 - If nothing runs, then double check everything
      - Otherwise, just run 'Cookie_Calculator.jar'
      - JavaFX will not load that way but nothing else is working