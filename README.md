# Verovio tutorial

A hands-on tutorial for exploring Verovio with GitHub Codespaces.

## Getting Started

1. Open the repository on GitHub.
2. Click "Fork" (top-right) and fork the repo (i.e., make a copy) into your own GitHub account
2. On your own fork, click Code → Codespaces → Create codespace on main.
2. Wait for the environment to start.
2. Open the provided HTML files in the browser preview and start experimenting. (See instructions below for web server setup)

## To Preview your Codespace files

1. Open the "Terminal" in Codespace (Bottom Panel)
1. Type: `python3 -m http.server 8000` on the command line; Verify that it starts a web server
1. Go to the "Ports" tab in the bottom panel
1. You should see Port 8000; Mouse-over the "Forwarded Address" and click the Globe icon 🌐
1. A new tab / window should open. Append the page you want to see at the end of the URL, e.g., "/editorial-markup.html" 

## Tutorial Exercises

Try the following tasks:

### 1. Display an MEI file

In index.html:

* Load and render an MEI file with Verovio
* Experiment with rendering options
* Try changing the zoom

### 2. Adjust SVG Styling

In css-and-svg.html:

* Modify the SVG appearance using CSS
* Change rest color
* Pass additional MEI attribute and highlight according to the value

### 3. Load Another Format

In musicxml.html:

* Load a MusicXML file instead of MEI
* Convert it to MEI

### 4. Play MIDI

In midi.html:

* Generate MIDI from the score
* Synchronize playback with score highlighting

## Python 

Fill the Python script in edit-demo/ 

* Loads an MEI file
* Save the SVG 

### Feeling adventurous?

Adjsut the script

* Edit it with the Verovio editing API,
* Re-render the layout,
* Save the updated MEI and SVG output.

See the JSON files for example actions

## Tips

* Use the browser developer tools to inspect the generated SVG.
* Check the Verovio documentation for rendering and editing APIs.

### Desperate?

See solutions in the [Reference book](https://book.verovio.org/first-steps/)
