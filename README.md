# Teaching Fractions — Cut a Whole

An interactive, visual fraction workshop for students and teachers. Cut a whole into equal pieces, compare fractions, drag and combine blocks, and reveal step-by-step solutions when you're ready.

**No installation, sign-in, server, frameworks, or internet connection required.** The entire application lives in [`index.html`](index.html).

## Try it

- **Online (GitHub Pages):** Once the repository is published and Pages is enabled, open `https://YOUR-USERNAME.github.io/teaching-fractions/` (replace `YOUR-USERNAME` with your GitHub username).
- **Offline:** Download [`index.html`](index.html) and open it in a modern desktop or mobile browser.

## Features

- **Cut a whole:** Right-click a block (or press and hold on touch) and divide it into **2, 3, 4, 6, or 8** equal pieces, subject to the app's size limits.
- **Enter a fraction directly:** From the cutting board's context menu, enter a numerator and denominator. For example, `3/4` displays a `3/4` block beside the remaining `1/4`; `5/2` displays two wholes and a half. The entered fraction is highlighted briefly.
- **Compare fractions:** Drag copies of cutting-board blocks into **A (top)** and **B (bottom)**. Their lengths share the same scale, making `=`, `<`, and `>` comparisons visible.
- **Combine fractions:** Click the comparison symbol to copy A and B into **Addition**, or drag blocks into the Addition area yourself. Drop one block onto another to combine them.
- **Preserve the pieces:** The Addition area keeps the original block labels and visually separates **Whole 1, Whole 2**, and further wholes if the total exceeds one. A block crossing a whole boundary continues into the next bar without becoming a new mathematical cut.
- **Simplify in steps:** Double-click or use **Simplify** to see an explanation. In Addition, an improper fraction such as `11/8` can first become `8/8 + 3/8`, then `1 + 3/8` when the full whole is simplified.
- **Answers on demand:** **Show Answer** buttons open worked-solution popups instead of immediately revealing totals. The board, A, B, comparison, and Addition have answer-reveal controls.
- **Temporary teaching arrows:** Hold the left mouse button and drag on empty page space to point at something. The arrow stays visible while held and fades a few seconds after release; dragging a fraction block still moves the block.
- **Classroom-friendly controls:** Undo, reset, ready-made comparison examples, a collapsible teacher guide, touch interactions, and disabled text selection outside editable fields.
- **Automatic colors:** Fraction colors are assigned locally by the denominator using a 32-color cycling palette; no external backend is needed.

## How to use

1. Open `index.html` or your published GitHub Pages URL.
2. **Right-click the cutting board** and select **Enter fraction…** to display a specific value, or choose **Cut into** to create equal pieces.
3. **Drag a piece from the cutting board** into A or B. Dragging from the board creates a copy, leaving the source piece available.
4. Repeat for the other comparison row. Click the displayed **`<`**, **`>`**, or **`=`** symbol to copy both rows into Addition, or drag individual blocks there.
5. Explore the whole boundaries, drag blocks together to join them, and double-click blocks to simplify or separate improper fractions.
6. Click **Show Answer** or **Show Comparison Solution** when you're ready for the calculation and explanation.

**Quick example:** Enter `3/4`, use it in a comparison, and try adding two copies. Another example is to merge pieces into `11/8`, then double-click to display `8/8 + 3/8`, followed by `1 + 3/8`.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named **`teaching-fractions`**.
2. Upload **the files inside this project folder** to the repository's root—not the ZIP itself. The root must contain `index.html`, `README.md`, and `LICENSE`.
3. Commit the files to the default branch (usually `main`).
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**; select **`main`** and **`/(root)`**, then save.
6. Once GitHub completes the deployment, your website will be available at:

   `https://YOUR-USERNAME.github.io/teaching-fractions/`

GitHub Pages serves `index.html` as the landing page automatically. No workflow configuration or compilation is required.

## Project structure

```text
teaching-fractions/
├── index.html   # Complete offline-ready learning activity (HTML + CSS + JS)
├── README.md    # Documentation and publishing instructions
└── LICENSE      # MIT license
```

## Technology and privacy

- Built with **HTML, CSS, and vanilla JavaScript**.
- Uses modern browser features such as pointer events, SVG, and HTML dialogs.
- Makes **no external network requests** in its current version and contains no advertising, analytics, accounts, or server-side storage.
- Runs locally or as a static website. No database or build tools are required.

## Contributions

Suggestions, bug reports, accessibility improvements, new fraction exercises, and pull requests are welcome. Please open an issue explaining the problem or proposed change, and include steps to reproduce any bugs.

## License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for the full text. You may reuse and adapt the source with the required copyright and license notice.
