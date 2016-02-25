This doucment walks throught the setup of **Sublime Text 3** for basic front-end development.

### Index

#### Intro
#### Setup Prerequisites
#### Install Package Control
#### Navigate with package Control
#### Install `SublimeLinter`
#### Install `SublimeLinter` Dependencies
#### Configure global user settings
#### Configure `SublimeLinter` user settings

### Why setting up your Sublime Text

This setup helps you to establish good coding habits, mainly:

- a 2-space indent

It also sets up three linters for html, css, and js, respectively. Linters are spellcheck for code. With linters in place, you can spend more time on acutal coding, and less on finding typos.

After you are done with the steps, consult [appendix0]() to see how everything works.

### Check Sublime Text version

You can check your Sublime Text version by going to `Sublime Text` --> `About Sublime Text`. If you see `Stable Channel. Build 3xxx` you are good. Otherwise download the latest Sublime Text on [its website](http://www.sublimetext.com/). (If you'd rather update it with `brew cask`, consult [appendix1]().)


![](http://cl.ly/2P0n2a283v2B/Screen%20Shot%202016-02-24%20at%204.40.22%20PM.png)

### Setup Prerequisites

Run the folloing in iTerm. If you wonder what these steps mean, consult [appendix2]().

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

This opens a file called `Preferences.sublime-settings`. Copy [the example]() to start. You can add or substract settings anytime.

### Configure `SublimeLinter` user settings

This makes use of all the packages you just installed.

`Sublime Text` --> `Preferences` --> `Packages Settings` --> `SublimeLinter` --> `Settings - User`

![](http://cl.ly/1p1h1x1b160A/Screen%20Shot%202016-02-24%20at%201.38.13%20PM.png)

This opens another setting file named `SublimeLinter.sublime-settings`. Copy [the example]() in the gist to start.
