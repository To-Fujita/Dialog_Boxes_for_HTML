# Dialog_Boxes_for_HTML

## 1. Description:
 The dialog element is now available in HTML 5.2. Then, I had tyied to create some samples for dialog boxes. The samples are included display the informations, input the data, read and write the files and to create the menu. I hope this article will help to beginners for programming.
[index.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/index.html): This is a menu to execute for all of the programs in this article.
 
## 2. Details:
 It is very easy to create a dialog box. The next code is to create a simple dialog box. It is needed to remember to create buttons that open and close for the dialog box.

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
 
### 2-1. Informations
(a) Information
 [EN_Dialog_001.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_001.html): "EN_Dialog_001.html" is a source file for basic information and with the effect of letters collapsing as like sands.
 
(b) Profile
 [EN_Dialog_010.html](https://to-fujita.github.io/Dialog_Boxes_for_HTML/EN_Dialog_010.html): "EN_Dialog_010.html" is a source file to display the picture with some effects.

### 2-2. Data Input
(a) Text Input

(b) Text Input by Voice

(c) Radio Button

(d) Check Box

(e) Selecter

(f) Calendar


### 2-3. File Read and Write
(a) Load the Text File 

(b) Load the CSV File

(c) Load the Image File


### 2-4. To Create Menu
(a) Drop Down Type of Menu

(b) Slider Type of Menu

(c) Icon Type of Menu


### 2-5. Others
(a) Digital Clock

 
## 3. Reference:


## 4. License:
MIT

## 5. Author:
[T. Fujita](https://github.com/To-Fujita)
