## Known Issues

- [ ] Editing local files does not sync changes to the source files on disk.
- [ ] Theme switching causes flicker in dark mode.
- [ ] Copying code: the green highlight does not display well in dark mode.
- [ ] PDF export may inherit browser's night mode color.
- [ ] After manually switching the webpage to dark mode, PDF export may appear lighter.
- [x] ~~Copy button: considering whether to sync with GitHub's overlapping small-square style; may affect display on different devices, or keep the original copy button for compatibility.~~  I will choose the original GitHub copy button for now.
- [ ] Line breaks: GitHub requires two spaces at the end of a line to break, but currently pressing Enter inserts a line break immediately; this behavior should be fixed.
- [ ] Scroll/slider progress: when sliding the progress bar, the left and right sides do not stay synchronized with the elements; needs to be fixed.
- [ ] GitHub relative paths: resources using relative paths cannot be found directly, because they depend on the repository name; need to use full paths.

*(These will be fixed in a future release.)*
