# Jupyter Notebook Widgets Presentations

The Jupyter Notebook application includes the widgets module *ipywidgets*.

This presentation is based around using the ipywidgets module version 7.5.1 which was the current stable version as of October 2019.

For the change log of the widgets module refer to: https://ipywidgets.readthedocs.io/en/latest/changelog.html

## Part 1

The *jupyter-widgets-presentation-1.ipynb* file is Part 1 of the presentation. The notebook becomes too large to easily scroll through so the presentation is continued in *jupyter-widgets-presentation-2.ipynb* file as Part 2.

Part 1 commences with the following as an introduction:

* Version check
* Help Information
* Grouping the Widgets into Catagories

The following catagories of widgets are then presented. A code example for each widget is provided to demonstrate its functionality:

* Boolean Switches: Button, Checkbox, ToggleButton

* Selections: Combobox, Dropdown, RadioButtons, Select, SelectMultiple, ToggleButtons

* Sliders: FloatLogSlider, FloatRangeSlider, FloatSlider, IntRangeSlider, IntSlider, SelectionRangeSlider, SelectionSlider

* Text: HTML, HTMLMath, Label, Password, Text, Textarea,

* Numeric: BoundedFloatText, BoundedIntText, FloatText, IntText

## Part 2

The file, *jupyter-widgets-presentation-2.ipynb*, is Part 2 of an introductory presentation of the widgets that are included with jupyter notebook.

This presentation is based around using the ipywidgets module version 7.5.1 which was the current stable version as of October 2019. Running the first cell below will check the version of ipywidgets.

This presentation highlights features from the following catagories of the ipywidgets classes:

* Tools: ColorPicker, DatePicker, IntProgress, FloatProgress.
* Media: Image, Audio, Video, Play.
* File Transfer: FileUpload

**NOTE:** This second presentation expects the sub-folder *image* containing the three media files:

* hampug_lawrence_2018_03_12.jpg
* sonata_pathetique_2nd_movement.mp3
* tree_cartoon.webm


### Copying Code Examples

Each widgets code example is designed so it is standalone and can be cut and pasted into another Jupyter notebook cell. The start and end of each widgets demonstration code is `#===`. For example to cut the whole of the Toggle button code start the cut at:
```
#=== ToggleButton Widget
toggle_button = ipywidgets.ToggleButton(
```
and copy all the code until:

```
display(ipywidgets.VBox([toggle_button, toggle_button_label,]))
#===
```

Once this is pasted into a new cell it should run and display as it is, with the exception that you may need to prefix it with `import ipywidgets`. This widgets code may then be adapted to suite your needs. The code uses *display* from `from IPython.display import display`. Jupyter notebook appear to automatically perform this import.
