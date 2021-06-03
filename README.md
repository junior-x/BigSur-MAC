<h1 align="center">BigSur-MAC</h1>
<h1 align="center">Theme for Ubuntu / GNOME</h1>


<h1 align="center">
  <image src="./source/homescreen1.png" /> <br>
  <image src="./source/homescreen2.png" /> <br>
  <image src="./source/homescreen1-1.png" /> <br>
</h1>

<!-- <h1 align="center">
  <image src="./source/homescreen2.png" />
</h1>

<h1 align="center">
  <image src="./source/homescreen1-1.png" />
</h1> -->

---

<h1 align="center">📨 FILES CONFIG</h1>

Update files in linux~

        ~$ sudo apt update

Then make hidden folder visibles

        ctrl + H

Search for any folders like `.themes` and `.icons` ...  If it`s not there create it

        ctrl + shift + N  

Now download the files from the repository and extract wich one inside they respectives folder`s. 

---

After all extracted time to move it~

        `.themes` get ->  `mkos-big-sur` + `mkos-BigSur-Dark-gtk`

        `.icons` get ->    `icones-Mkos-Big-Sur` + `Cursor-macOSBigSur`

---
<h1 align="center">🧲 SYSTEM SET-UP</h1>

<h3>GNOME TWEAKS</h3>

Start `>_ Terminal` 

        ~$ sudo apt-get update
.

        ~$ sudo apt-add-repository universe
.

        ~$ sudo apt install gnome-tweak-tool
.

        ~$ gnome-tweaks

---        

Now time to install the `>_ .extensions` and `.activated`

        ~$ apt search gnome-shell-extension
.

        ~$ sudo apt install gnome-shell-extension-User_Themes
.
        
        ~$ sudo apt install $(apt search gnome-shell-extension | grep ^gnome | cut –d / -f1)
.

        ~$ sudo apt install gnome-shell-extension-Dash_to_Dock
.
        
        ~$ sudo apt install $(apt search gnome-shell-extension | grep ^gnome | cut –d / -f1)

---

*If everything get cool, you should open the App, then you just need to make then look like this*


<h1 align="center"><image src="./source/homescreen3.png" /></h1>

---

<h3 align="center">Enjoy! :)</h3>