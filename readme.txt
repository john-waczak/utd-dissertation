# Build Information

To build the pdf using latexmk, run the following command:

```bash
$> latexmk -pdf
```

To continuously rebuild and preview the changes, run
```bash
$> latexmk -pdf -pvc
```

To clean up intermediate files afterwards, run
```bash
$> latexmk -c
```

**NOTE**: For continuous preview on mac-os use [Skim](https://sourceforge.net/projects/skim-app/) and set the configuration file at `$HOME/.latexmkrc` to
```
$pdf_previewer = `open -a Skim`
```
