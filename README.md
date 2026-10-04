# Decision Tree Builder

A simple, free decision tree tool that runs in your browser. No install, no account, no internet needed. Build a tree of questions with custom answers, then run it to reach a decision.

It is a single file (`decision-tree.html`). Your trees are saved as small `.json` files on your own computer.

## What it does

- Build trees with boxes, answers, and arrows that update automatically when you move boxes
- Custom answer labels for each question (Yes/No, Accept/Reject/Review, Unclear, and so on)
- Colours with meanings you can rename (for example Proceed, Review, Stop)
- Notes on any box for extra instructions
- **Run Mode:** answer one question at a time and see your path and the final decision
- **Clean view:** a simple read-only look at your tree
- Zoom with the mouse wheel, drag empty space to move around, and Fit to see the whole tree
- Export the whole tree as a PNG picture
- Undo, Redo, Copy a box, Save, and Save As

## How to use it

1. Download `decision-tree.html`.
2. Double-click it. It opens in Chrome or Edge.
3. Click **Open** and choose `sample-headphones-tree.json` to see an example, then click **Run Tree**.
4. To build your own, click **New** (or **Edit tree**), type a question, and click **+ Box** next to an answer to create the next box.
5. Click **Save** to keep your tree. Click **Open** later to load it again.

## Keyboard shortcuts

| Keys | Action |
| --- | --- |
| Ctrl + S | Save |
| Ctrl + Shift + S | Save As |
| Ctrl + O | Open |
| Ctrl + Z | Undo |
| Ctrl + Y | Redo |
| Esc | Leave Run Mode |

## Limits

- Made for a laptop or desktop with a mouse, in Chrome or Edge. It is not designed for phones.
- PNG export shows boxes, arrows, answer labels, and a colour legend. Notes are not included.
- Zoom level is not saved in your file.
- Version 1. Search and a Windows installer (.exe) are possible future additions.

## Built with

Plain HTML, CSS, and JavaScript in one file. Built step by step with the help of Claude, an AI assistant.

## License

MIT License. Free to use and change.
