# Devlog - OpenQR

This is a development log I've decided to create for this project, as I'd like to talk about what I've been up to with the project, even if it's not quite woth pushing a commit to a branch.
Or, I've spent ages trying to understand a really backward implementation, just to find a way simpler way to do the same thing hours later... not relatable at all :)

## 28/09/2025 - Making images work

Turns out images in custom tkinter are a lot more complicated than I originally thought.
And infinite wisdom to choose custom tkinter to make things look prettier, it just things more complicated again

Theoretically, this is how it should work:
```
root = Tk()

ctk.CTkLabel(root, 
  text = 'This is a label', 
  text_font =('Verdana', 17)).pack(side = LEFT, pady = 11)

img = PhotoImage(file="./img/back-button.png")
ctk.CTkButton(master = root, image = img).pack(side = LEFT)

```

And this was the way more or less I got it working, and an image did pop up in then UI, however I couldn't find out how exactly how to make it not then standard image size, as to view it I've currently got to make the window very wide (basically the size of my screen). 

Note: Doing a small bit of research later, it looks possible, but annoyingly verbose coming from primarily python and basic tailwind web development

Fingers crossed I can get a bit of progress done soon, after getting the images in I'll focus on the UI layout to get a working UI.
Then hopefully having the QR code image update every time a new one is generated may be automatic or can be fairly easily refreshed.

##
