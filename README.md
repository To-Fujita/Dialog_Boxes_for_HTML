# Dialog_Boxrs_for_HTML

## 1. Description:
 The dialog element is now available in HTML 5.2. Then, I had tyied to create some samples for dialog boxes. The samples are included display the informations, input the data, read and write the files and to create the menu. I hope this article will help to beginners for programming.
 
## 2. Details:
 It is very easy to create a dialog box.  
 
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
 
 
## 3. Reference:

## 4. License:
MIT
## 5. Author:
[T. Fujita](https://github.com/To-Fujita)
