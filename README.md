# Dialog_Boxes_for_HTML

## 1. Description:
 The dialog element is now available in HTML 5.2. Then, I had tyied to create some samples for dialog boxes. The samples are included display the informations, input the data, read and write the files and to create the menu. The dialog element is supported by Chrome and Microsoft Edge. I hope this article will help to beginners for programming.  
 
## 2. Demo:

<img src="https://to-fujita.github.io/Images/Dialog_Animation.gif" alt="Dialog_Animation" title="Dialog_Animation" width="374" height="300">  

[index.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/index.html): This is a menu to execute for all of the programs in this article.  
 
## 3. Details:
 It is very easy to create a dialog box. The next code is to create a simple dialog box. It is needed to remember to create buttons that open and close for the dialog box.  
 [Simple_Dialog.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/Simple_Dialog.html): To show a simple dialog box.  

 ~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset = "utf-8" />
        <title> Simple Dialog Box 2021/06/10 by T. Fujita</title>
    </head>
    <body>
        <center>
            <p>Simple Dialog Box</p>
            <input type="button" value="Open dialog" onclick="dialog_Open()">    
        </center>
        <dialog id="dialog">
            <center>
                <p>This is a simple dialog box.</p>
                <br>
                <input type="button" value="Close dialog" onclick="dialog_Close()">
            </center>
        </dialog>
        <script>
            function dialog_Open(){
                dialog.showModal();
            }
            function dialog_Close() {
                dialog.close();
            }
        </script>
    </body>
</html>
 ~~~
 
### 3-1. Informations
(a) Information  
 [EN_Dialog_001.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_001.html): "EN_Dialog_001.html" is a source file for basic information and with the effect of letters collapsing as like sands.
 
(b) Profile  
 [EN_Dialog_010.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_010.html): "EN_Dialog_010.html" is a source file to display the picture with some effects.

### 3-2. Data Input
(a) Text Input  
 [EN_Dialog_002.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_002.html): "EN_Dialog_002.html" is a source file to input the text by keyboard.  

(b) Text Input by Voice  
 [EN_Dialog_012.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_012.html): "EN_Dialog_012.html" is a source file to input the text by voice recognition.  
 
(c) Radio Button  
 [EN_Dialog_003.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_003.html): "EN_Dialog_003.html" is a source file by using radio button.  
 
(d) Check Box  
 [EN_Dialog_004.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_004.html): "EN_Dialog_004.html" is a source file by using check box.  
 
(e) Selecter  
 [EN_Dialog_005.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_005.html): "EN_Dialog_005.html" is a source file by using pull down selecter.  
 
(f) Calendar  
[EN_Dialog_011.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_011.html): "EN_Dialog_011.html" is a source file by using date picker on calendar.  

(g) Slider  
[EN_Dialog_018.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_018.html): "EN_Dialog_018.html" is a source file to input the numbers by using slider.

### 3-3. File Read and Write
(a) Load the Text File  
 [EN_Dialog_006.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_006.html): "EN_Dialog_006.html" is a source file to load the text file from local device. This program is supported several type of character sets. It is supported by the "EN_Dialog_100.html" and by the "EN_Dialog_102.html" to save the text file with UTF-8 of character set.  
 
(b) Load the CSV File  
 [EN_Dialog_007.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_007.html): "EN_Dialog_007.html" is a source file to load the CSV file from local device. This program is supported several type of character sets. It is supported by the "EN_Dialog_100.html" and by the "EN_Dialog_102.html" to save the text file with "UTF-8" or "Shift-JIS (ANSI)" of character set.  
 
(c) Load the Image File  
 [EN_Dialog_008.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_008.html): "EN_Dialog_008.html" is a source file to load the image file from local device.  

### 3-4. To Create Menu
(a) Drop Down Type of Menu  
 [EN_Dialog_100.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_100.html): "EN_Dialog_100.html" is a source file to show the drop down menu and link to sevral dialog boxes.  
 
(b) Slider Type of menu   
 [EN_Dialog_101.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_101.html): "EN_Dialog_101.html" is a source file to show the slider type of menu by a dialog box.  
 
(c) Icon Type of Menu  
[EN_Dialog_102.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_102.html): "EN_Dialog_102.html" is a source file to show the icon type of menu and link to sevral dialog boxes.  

(d) Block Type of Menu  
[EN_Dialog_103.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_103.html): "EN_Dialog_103.html" is a source file to show the block type of menu with icons and link to sevral dialog boxes.  

### 3-5. Others
(a) Digital Clock  
 [EN_Dialog_009.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_009.html): "EN_Dialog_009.html" is a source file for the digital clock in the dialog box.  
 
 (b) Analog Clock  
 [EN_Dialog_016.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_016.html): "EN_Dialog_016.html" is a source file for the analog clock in the dialog box.  
 
 (c) Color Picker  
  [EN_Dialog_017.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_017.html): "EN_Dialog_017.html" is a source file for the color picker in the dialog box.  
 
 (d) Color Maker with Sliders
  [EN_Dialog_019.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_019.html): "EN_Dialog_019.html" is a source file for the color maker with sliders in the dialog box.  
 
## 4. Reference:
- [The Dialog Element](https://developer.mozilla.org/en/docs/Web/HTML/Element/dialog)

## 5. License:
MIT

## 6. Author:
[T. Fujita](https://github.com/To-Fujita)
