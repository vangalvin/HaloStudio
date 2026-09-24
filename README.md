# Halo Studio

Halo Studio is a Windows pattern editor for Phantom Flow POV devices.

Use it to draw LED patterns, import images, create text banners, preview the result as a spinning POV display, and save projects as `.halostudio` files.

## Download

Download the latest Windows installer from the Releases page:

https://github.com/vangalvin/HaloStudio/releases/latest

Under **Assets**, download:

`HaloStudioSetup-1.0.0.exe`

Using the Releases download helps us count how many times the installer has been downloaded.

## Install

1. Run `HaloStudioSetup-1.0.0.exe`.
2. Follow the installer prompts.
3. Launch **Halo Studio** from the desktop shortcut or from the Windows Start Menu.

The installer includes Halo Studio, example patterns, example images, Start Menu shortcuts, a desktop shortcut, uninstall support, and `.halostudio` file association.

## Windows Support

Halo Studio currently supports:

- Windows 10, 64-bit
- Windows 11, 64-bit

## Windows Security Warning

This early test installer is not code-signed yet, so Windows may show a warning such as **Windows protected your PC**.

If you trust this download source:

1. Click **More info**.
2. Click **Run anyway**.

## First Launch

When Halo Studio opens, you will see:

- The pattern editor on the left.
- The spin preview on the right.
- A menu button in the top-right corner for file actions, licence, and about information.

The top bar shows the current pattern size, selected tool, demo/pro status, and app status.

## Open The Included Examples

The installer includes example patterns and images.

After installing, open:

**Start Menu > Halo Studio > Examples**

You can:

- Double-click a `.halostudio` file to open it in Halo Studio.
- Use **Open...** from the top-right menu to open a `.halostudio` file.
- Use **Import PNG** to bring one of the example PNG images into the editor.

## Pattern Workspace

The workspace is a pixel grid.

- **Height** is the number of LEDs in the strip.
- **Width** is the number of pattern columns.
- Use **24 px** or **48 px** for common Halo layouts.
- Enter a custom **Height** if you are designing for another device.
- Enter a custom **Width** for longer or shorter patterns.
- Use **Zoom** to make the editor easier to work with.
- Use **Pattern name** to name the project.

If the pattern is wider than the screen, use the horizontal scrollbar under the editor.

## Drawing Tools

Use the **Brush Tools** section to choose how you want to edit the pattern.

Available tools:

- **Pencil**: draw individual pixels or drag to paint.
- **Eraser**: remove pixels.
- **Fill**: fill connected areas.
- **Line**: draw straight lines.
- **Rect**: draw rectangles.
- **Circle**: draw circles.
- **Arc**: draw curved strokes.

Right-clicking on the canvas can be used as a quick erase action while drawing.

Use **Fill rectangle and circle shapes** if you want rectangle and circle tools to create filled shapes instead of outlines.

## Palette And Custom Colours

Use the colour squares in **Palette** to choose a drawing colour.

To create a custom colour:

1. Click **Pick**.
2. Choose or mix a colour.
3. Confirm the colour.

The custom colour is added to the custom colour slots. If you select an existing custom colour slot first, **Pick** will replace that selected custom colour.

Use **Pick Pixel** to sample a colour directly from the pattern canvas.

## Basic Pattern Actions

Use the action buttons above the tools:

- **New**: start a fresh pattern.
- **Undo / Redo**: step backwards or forwards through changes.
- **Clear**: clear the canvas.
- **Mirror H**: mirror horizontally.
- **Mirror V**: mirror vertically.
- **Shift arrows**: move the pattern left, right, up, or down.
- **Import PNG**: import an image into the current pattern.
- **Save PNG**: export a PNG image. This is a Pro feature.

## Importing PNG Images

Click **Import PNG** and choose an image file.

The **Import Mode** setting controls how the image is fitted:

- **Scale to height**: scales the image to match the LED height.
- **Fit inside canvas**: fits the whole image inside the current canvas.
- **Zoetrope strip**: imports the image as a zoetrope-style strip.

If the result is not what you expected, use **Undo**, change the import mode, and import again.

## Text Banner

The **Text Banner** section turns typed text into a pixel pattern.

1. Type the text you want.
2. Choose **Pixel font** or **System font**.
3. Choose the text alignment.
4. Use **Full LED height** if you want the text to fill the strip height.
5. Use the font picker to select a Windows system font.
6. Click **Generate Banner**.

Use **Auto width** if you want Halo Studio to resize the pattern width to fit the generated text.

## Spin Preview

The **Spin Preview** shows how the pattern may appear when spinning.

Preview modes:

- **Static wrap**: shows the pattern wrapped around the circle.
- **Animated wrap**: animates the pattern around the circle.
- **Persistence view**: simulates persistence-of-vision trails.

Useful preview controls:

- **RPM**: simulated spin speed.
- **Direction**: clockwise or counter-clockwise.
- **Pattern repeats**: how many times the pattern repeats around the circle.
- **Brightness**: preview brightness.
- **Persistence**: amount of light trail in the preview.
- **Exposure**: width of the visible persistence trail.
- **1st LED offset**: distance from the handle/centre to the first LED.
- **LED pitch**: spacing between LEDs.

The preview is a simulation to help design the pattern. Real-world results can vary depending on device, LED spacing, spin speed, brightness, and camera exposure.

## Zoetrope Strip

The **Zoetrope Strip** tools are for patterns that use multiple animation frames inside one strip.

Basic workflow:

1. Turn on **Enable zoetrope**.
2. Choose the number of **Frames**.
3. Set the **Frame width**, or leave **Auto-fit canvas** enabled.
4. Use **Current frame** to edit a frame.
5. Use **Copy Previous** to duplicate the previous frame.
6. Use **Clear Frame** to clear only the selected frame.
7. Use **Play preview** to preview the animation.

Use **Apply Strip Size** if you want Halo Studio to resize the canvas to match the selected frame layout.

## Saving And Opening Projects

Halo Studio project files use the `.halostudio` extension.

Use the top-right menu:

- **New**: create a new project.
- **Save**: save to the current file.
- **Save As...**: choose a new file name and location.
- **Open...**: open a `.halostudio` file.
- **Open Recent**: reopen one of the last files you worked on.

If you choose **Save** before the project has a file name, Halo Studio will ask where to save it.

The pattern name is based on the file name when a project is opened or saved.

## Demo And Pro Features

The demo version allows you to create, edit, import, preview, save, and reopen Halo Studio project files.

Pro/licensed features are intended for exporting patterns to external formats such as PNG/JPG/BMP and device-specific formats.

Use the top-right menu and choose **Licence** to enter a licence key.

## Tips For Testers

Please try:

- Installing Halo Studio on Windows 10 or Windows 11.
- Opening the included example `.halostudio` files.
- Importing the included PNG images.
- Drawing with each brush tool.
- Creating a text banner using a Windows system font.
- Saving a project with **Save As...**.
- Closing and reopening the saved project.
- Double-clicking a `.halostudio` file to open it.
- Uninstalling Halo Studio from Windows Apps/Programs.

## Feedback

Please send feedback, bug reports, and screenshots to:

`vangalvin@live.com`

Useful feedback includes:

- What you were trying to do.
- What happened.
- What you expected to happen.
- Your Windows version.
- A screenshot if something looks wrong.

Copyright 2026 Andrew Hooper. All rights reserved.
