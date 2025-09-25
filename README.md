# What's Open-QR?
An open source app for creating QR codes with logos, colour styles and various styles, using python-qrcode.

Why make this?
Because I haven't found a QR code maker that's everything it should be, given how relitively simple they are to make, especially seeing all of the apps and websites that are charging for the simple QR code making.
I do know that versions of this do exist, but I wanted to make one that's both open source, and user friendly. (and not javascript... unless I must)
More importantly I wanted better customisation, everything from images to backgrounds to main colours of the QR code, images you can make them into, maybe even exportable styles! (Though that's a ways off yet)

# Roadmap

- [x] ~~Create the first working'prototype~~
- [ ] Allow for complete user selection on as many options as possible, colours, custom logos etc.
- [ ] Use a GUI framework to create a desktop app (Maybe tkinter?)
- [ ] Make a web version
- [ ] Get funding to host the website
More coming soon... (suggestions welcome!)

# What did you use to build this?
For the backend I'm using the python-qrcode library as it's simple to use, and I know python. I didn't feel a need for millisecond load times on a QR code generator, and more complex code
The frontend is slightly up for debate, at the moment (Mid-late 2025) I'm using tkinter, because it's interesting and I wanted to make a quick GUI for the first prototype, but I'll probably change the frontend in the future.
I'm probably going to start with something web based, with desktop apps using tauri (There's a win for the non electron lovers) and maybe I'll even make native apps, but only if it makes sense, after all it's a QR code generator, not an intensive benchmark :).

## Will this come to [PLATFORM]?
The tauri app should make cross platform fairly simple so... hopefully, but I plan to have a self hostable web version too, so that might be simpler.
If you really want me to make a native mac app, I don't have access to a mac, so if this little project is what you're gunning for, try it yourself! or I have a ko-fi link below if you'd like to support me starting to develop on mac.

Fuel my coffee needs or donate towards my dev journey! (All donations are 100% optional and will NEVER be required)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S31EC98I)
