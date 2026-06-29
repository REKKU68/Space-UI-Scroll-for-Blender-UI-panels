# Space UI Scroll

<img width="717" height="629" alt="space_ui_scroll" src="https://github.com/user-attachments/assets/9dd4392b-7a52-46e0-afad-b6e759830d38" />

Space + Left Mouse drag scrolling for Blender UI panels.

A small Blender addon that allows scrolling UI panels (N-panel, Properties, Outliner, etc.) by holding **Space** and dragging with **Left Mouse Button**, similar to Clip Studio Paint.

---

## Features

* Hold **Space**
* Drag with **Left Mouse Button**
* Scroll UI panels by dragging
* Works with:

  * N-panel
  * Properties editor
  * Outliner
  * Other View2D-based UI regions

If Space is pressed and released without dragging, Blender's Search Menu is opened, preserving the default behavior.

---

## Why?

Tablet users often struggle with Blender's thin scrollbars.

This addon provides a workflow similar to Clip Studio Paint:

* Hold Space
* Drag anywhere
* Scroll naturally

This makes long UI panels much easier to navigate when using a pen tablet.

---

## Usage

| Action                  | Result       |
| ----------------------- | ------------ |
| Space press + release   | Search Menu  |
| Space + Left Mouse Drag | UI scrolling |
| Right Mouse or ESC      | Cancel       |

---

## Installation

1. Download the addon `.py` file.
2. Open Blender.
3. Go to:

Edit → Preferences → Add-ons → Install

4. Select the file.
5. Enable **Space UI Scroll**.

---

## Supported Blender Version

* Blender 4.5+

---

## Notes

This addon uses Blender's `view2d.pan` operator.

Scrolling behavior depends on whether the UI region supports View2D panning.

---

## Ideal For

* Pen tablet users
* Artists coming from Clip Studio Paint
* Users who dislike narrow scrollbars
* Large N-panel workflows
* Long Property editor pages

---

## License

GPL License
