# Processing Bundle for Sublime Text 2

A [Processing](http://processing.org/) bundle for [Sublime Text
2](http://www.sublimetext.com/2). Check the [demo
video](https://vimeo.com/45573600) on Vimeo! Please note: you must have
Processing 2.0b6 or greater, otherwise the Build System of the bundle won't
work. The video is a bit outdated, you  no longer need to have the Processing
application open to run sketches. If, for any reason, you work with and older
version of Processing, e.g. 1.5.1, you can use the [old
version](https://github.com/b-g/processing-sublime/tags) of this package.

<a href="https://vimeo.com/45573600" target="_blank"><img src="https://github.com/b-g/processing-sublime/raw/master/Images/overview.png"></a>


## Configuration

### OSX

The `processing-java` command line tool must be installed from within the
Processing.app. From the menu bar, select `Tools -> Install "processing-java"`.

![processing-java command line tool](https://github.com/b-g/processing-sublime/raw/master/Images/processing_preferences.png)

### Linux

The Processing application must be added to your `PATH`, e.g.:

    export PATH=$PATH:/opt/processing/processing-2.0b4

### Windows

You will need to set your PATH environment variable to where your processing
application is located:

- Select Computer from the Start menu
- Choose System Properties from the context menu
- Click Advanced system settings > Advanced tab
- Click on Environment Variables, under System Variables, find PATH, and click
  on it
- In the Edit windows, modify PATH by adding the location of the Processing
  application. Each entry is separated with a semicolon.


## Installation

There are 3 easy ways to install the Processing Bundle:

### Using the Sublime Package Control

If you are using [Sublime Package
Control](http://wbond.net/sublime_packages/package_control), you can easily
install the Processing Bundle via the `Sublime Text 2 -> Preferences -> Package
Control: Install Package` menu item.

### Using Git

Alternatively, you can install the bundle and keep it updated by cloning the
repo directly into your `Packages` directory of Sublime Text 2.

Go to your Sublime Text 2 `Packages` directory and clone the  repository using
the command below:

    git clone https://github.com/b-g/processing-sublime/ Processing

### Downloading Manually

- Download the files using the GitHub .zip download option
- Unzip the files and rename the folder to `Processing`
- Copy the folder to your Sublime Text 2 `Packages` directory, e.g. OS X:
  `~/Library/Application Support/Sublime Text 2/Packages/Processing`


## Usage

- From within Sublime Text, select the Processing Build System: `Tools -> Build
  System -> Processing`
- Run the sketch: `super+b`
- With `super+shift+b` and typing `build` you get alternative buildsystems: `Run
  sketch fullscreen` and various `Export sketch options`

## Hints

- Console error messages are clickable, e.g.: double click `test.pde:10:0:10:0:
  The function reect(int, int, int, int) does not exist.` to jump to the related
  line and file.

## Getting Started With Sublime Text

If you are new to Sublime, the excellent and free video tutorial by nettuts is
recommended: [Perfect Workflow in Sublime
Text](http://net.tutsplus.com/articles/news/perfect-workflow-in-sublime-text-
free-course/). If you are short on time, then make sure you watch at least the
lesson [Multiple Cursors and Incremental Search]( https://tutsplus.com/lesson
/multiple-cursors-and-incremental-search/) (~6min), highly recommended!

## Acknowledgements

- This bundle is heavily based on [Processing TextMate Bundle by Leon
  Hong](http://www.onebitwonder.com/projects/processing/), thanks for all the
  good work!
- I used the [textmate-to-sublime-converter](https://github.com/srbs/textmate-
  to-sublime-converter) to convert the snippets from the original Processing
  TextMate Bundle to Sublime Text.
- Syntax highlighting tweaking [Mark Brand](https://github.com/ignism)
- Linux build script and testing [Julien Deswaef](http://xuv.be/)
- Windows build script and documention [Ralf Baecker](http://github.com/rlfbckr)
- Error console capturer [Greger Stolt Nilsen](http://gregerstoltnilsen.net/)
