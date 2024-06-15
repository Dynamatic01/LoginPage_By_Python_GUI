# LOGIN PAGE

A "Login Page by Python" typically refers to a user interface designed for authentication, built with Python programming language. It serves as the entry point for users to access an application by entering their credentials, usually a username and password. This page often includes form validation, secure password handling, and may interact with a database or authentication service to verify user details.

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## CODE

```javascript
from tkinter import *
from PIL import Image, ImageTk
win = Tk()
win.title("LOGIN PAGE")

def getvals():

    lbl2= Label(win, text="Your username is :" + usernameentry.get())
    lbl2.grid(row=5, column=3)
    lbl3= Label(win, text="Your password is :" + pswentry.get())
    lbl3.grid(row=6, column=3)




win.geometry("333x222")

lbl= Label(win, text="Login to Continue", font="comicsansms 13 bold", pady=15)
lbl.grid(row=0,column=3)


username = Label(win, text="User Name :")
psw = Label(win, text="Password :")
username.grid(row=1,column= 2)
psw.grid(row=2,column=2)



user_name= StringVar()
psw_value= StringVar()
check_value =IntVar()

usernameentry = Entry(win,textvariable=user_name)
pswentry = Entry(win,textvariable=psw_value)
usernameentry.grid(row=1,column=3)
pswentry.grid(row=2,column=3)

check = Checkbutton(text="Remember this device", variable=check_value)
check.grid(row=3,column=3)
Button(text="Login", command=getvals).grid(row=4,column=3)

win.mainloop()
```


## License

[GNU](https://github.com/Dynamatic01/LoginPage_By_Python_GUI/blob/main/LICENSE)


## Related

Here are some related projects

[Awesome README](https://github.com/Dynamatic01/Shutdown_GUI_By_Python.git)


## Support

For support, email mehtamohit514@gmail.com or join our Slack channel.


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohit-mehta-726179307/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/Dynamatic_699)
