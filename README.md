This doucment walks you through the setup of **Sublime Text 3** for basic front-end development (html/css/js).

### Index

#### 1. [Intro](https://github.com/jueyang/sublime-setup#why-setting-up-your-sublime-text)
#### 2. [Setup Prerequisites](https://github.com/jueyang/sublime-setup#setup-prerequisites-1)
#### 3. [Install Package Control](https://github.com/jueyang/sublime-setup#install-package-control-for-sublime-text)
#### 4. [Navigate with package Control](https://github.com/jueyang/sublime-setup#navigate-with-package-control-1)
#### 5. [Install `SublimeLinter`](https://github.com/jueyang/sublime-setup#install-sublimelinter-via-package-control)
#### 6. [Install `SublimeLinter` Dependencies](https://github.com/jueyang/sublime-setup#install-sublimelinter-dependencies-via-package-control)
#### 7. [Configure global user settings](https://github.com/jueyang/sublime-setup#configure-sublime-text-global-user-settings)
#### 8. [Configure `SublimeLinter` user settings](https://github.com/jueyang/sublime-setup#configure-sublimelinter-user-settings-1)
#### 9. [Done!](https://github.com/jueyang/sublime-setup#done)

### Why setting up your Sublime Text

This setup helps you to establish good coding habits, mainly:

- auto-complete with key words
- a 2-space indentation (hard tab)

It also sets up three linters for html, css, and js, respectively. **Linters are the spell check for code**. With linters in place, you can spend more time on acutal coding, and less on finding typos.

### Check Sublime Text version

You can check your Sublime Text version by going to `Sublime Text` --> `About Sublime Text`. If you see `Stable Channel. Build 3xxx` you are good. Otherwise download the latest Sublime Text on [its website](http://www.sublimetext.com/). (If you'd rather update it with `brew cask`, consult [appendix1](https://github.com/jueyang/sublime-setup/blob/master/appendix1.md).)


![](http://cl.ly/2P0n2a283v2B/Screen%20Shot%202016-02-24%20at%204.40.22%20PM.png)

### Setup Prerequisites

Run the folloing in iTerm. If you wonder what these steps mean, consult [appendix2](https://github.com/jueyang/sublime-setup/blob/master/appendix2.md).

- `brew update`
- `brew install node`
- `npm install -g csshint`
- `npm install -g jshint`
- `npm install -g tidy-html5`

### Install Package Control for Sublime Text

Follow [these instructions]((https://packagecontrol.io/installation#st3)).

### Navigate with Package Control

- In Sublime, open the console ``` ctrl + ` ```
- In Sublime, open the prompt `cmd` + `shift` + `p`
- In the prompt type `package control`. Choose from the dropdown `Package Control: Install Package`

  ![](http://cl.ly/0x303v0Q310w/Screen%20Shot%202016-02-24%20at%204.42.00%20PM.png)

- A moment later your prompt will show all the packages availabe for installation

### Install `SublimeLinter` via Package Control

- If you don't have the console or prompt open, repeat the first two steps from above.
-  In the prompt type `SublimeLinter`
  - You sould see a package named exactly as `SublimeLinter` (not `sublimelint` or `sublimelove`)
  - Hit `enter`

### Install `SublimeLinter` dependencies via Package Control

- In the same way you installed `SublimeLinter`:
  - Install `SublimeLinter-csshint`
  - Install `SublimeLinter-jshint`
  - Install `SublimeLinter-html-tidy`.

### Configure Sublime Text global user settings

This includes whether or not you want autocomplete, tab completion, etc.

`Sublime Text` --> `Preferences` --> `Settings - User`

![](http://cl.ly/0V290u1j271Q/Screen%20Shot%202016-02-24%20at%201.38.03%20PM.png)

This opens a file called `Preferences.sublime-settings`. Copy [the example](https://github.com/jueyang/sublime-setup/blob/master/Preferences.sublime-settings) to start. Remeber to save. You can add or substract settings anytime.

### Configure `SublimeLinter` user settings

This makes use of all the packages you just installed.

`Sublime Text` --> `Preferences` --> `Packages Settings` --> `SublimeLinter` --> `Settings - User`

![](http://cl.ly/1p1h1x1b160A/Screen%20Shot%202016-02-24%20at%201.38.13%20PM.png)

This opens another setting file named `SublimeLinter.sublime-settings`. Copy [the example](https://github.com/jueyang/sublime-setup/blob/master/SublimeLinter.sublime-settings) to start. Remember to save.

### Done!

After you are done with the steps, consult [appendix3](https://github.com/jueyang/sublime-setup/blob/master/appendix0.md) to see how everything works.
