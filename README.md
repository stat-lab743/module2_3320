# Lab 3: Z-Score Explorer

A standalone interactive for an online Behavioral Statistics/Psychology course. Students explore here and submit a separate paper in Canvas. The tool does not collect or save answers.

## Open offline

Open `index.html` in a web browser. No installation, external libraries, or internet connection is required.

## Publish with GitHub Pages

1. Extract this ZIP on your computer. Upload the extracted files, not the ZIP.
2. Create a new GitHub repository, for example `lab3-z-score-explorer`. A public repository is the simplest option for a publicly accessible course tool.
3. Use **Add file → Upload files** (or the new repository's **uploading an existing file** link). Upload `index.html`, `README.md`, and `.nojekyll` to the top level of the repository. Do not put them inside another folder. The empty `.nojekyll` file disables Jekyll processing; the standalone HTML also works without it.
4. Commit the uploaded files to `main`.
5. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select **main** and **/ (root)**, then **Save**.
6. Wait for deployment to finish. The Pages settings will display your published website link. Open it to check the explorer.
7. Share that website link in Canvas. Students submit their papers through your separate Canvas assignment.

For a repository named `lab3-z-score-explorer`, the usual address is `https://YOUR-USERNAME.github.io/lab3-z-score-explorer/`. Use the actual address shown in Pages settings.

If you see a 404, check that `index.html` is at the top level of the selected branch and that the Pages deployment has completed.

Official instructions: [Configure a GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Included activities

- Live z-score calculation and illustrative bell curve
- Keyboard-accessible sliders and number inputs for X, mean, and standard deviation
- Memory recall, attention, reaction time, and perceived stress scenarios
- Seven guided investigations with matching paper prompts
- Temporary starting-point comparison for the one-value-change challenge
- Scenario reset, whole-lab reset, random scores, and practice challenges
- Responsive layout for phones and larger screens

The scenarios are fictional teaching examples. Refreshing or closing the page clears the current exploration. Students should record values and interpretations in their papers before leaving.

## Files

- `index.html`: the complete explorer, including all styling and JavaScript
- `README.md`: these instructions
- `.nojekyll`: an empty GitHub Pages configuration marker

No build process or package installation is needed.
