# Cover Letter Updater
Hello all, I have created a simple python script that can update your cover letter to match a position automatically by taking in dynamic parameters modifying a template and producing a cover letter that is ready for submission \n
The script takes in a company name, optional company adress, position name, position posting location and a nifty feature which allows you to chosse a different body type depending on the type of position you are applying for ei. App Developer, Web Developer, Software Engineer... \n
The script uses a .DOCX cover letter template which I strongly suggest you modify the static fields to fit your profile. It then replaces the dynamic fields mentioned previously and converts to pdf format. 

# How to Run:
you will need python-docx library\n
$ pip install python-docx\n
now run the script\n
$ python updatecl.py