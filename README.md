# BibliaLS Fonts for Missing PDF Font Errors

Some older academic PDFs and Logos/Libronix-era documents reference the
`BibliaLS` font family, especially:

- `BibliaLS`
- `BibliaLS-Bold`
- `BibliaLS-Italic`
- `BibliaLS-BoldItalic`

If these fonts are missing, PDF readers may show errors such as:

> Cannot find or create the font `BibliaLS-Italic`

This is common with specialized biblical studies, Greek, and Hebrew texts that were produced using older Logos/Libronix fonts.

## Where to Get the Fonts

The fonts are included in the official Logos 3 / Libronix 3.0g installer ZIP:

https://www.logos.com/media/tech/Zip/LIbronixDLS-3.0g.zip

They are located inside the ZIP at:

```text
Setup/Fonts/BibLS.ttf
Setup/Fonts/BibLSB.ttf
Setup/Fonts/BibLSI.ttf
Setup/Fonts/BibLSBI.ttf
```

These map to the font names commonly requested by PDFs:

| File | Font name |
| --- | --- |
| `BibLS.ttf` | `BibliaLS` |
| `BibLSB.ttf` | `BibliaLS-Bold` |
| `BibLSI.ttf` | `BibliaLS-Italic` |
| `BibLSBI.ttf` | `BibliaLS-BoldItalic` |

## Windows Install Steps

1. Download the official Logos installer ZIP:
   https://www.logos.com/media/tech/Zip/LIbronixDLS-3.0g.zip
2. Open the ZIP file.
3. Go to `Setup/Fonts/`.
4. Extract these four files:
   - `BibLS.ttf`
   - `BibLSB.ttf`
   - `BibLSI.ttf`
   - `BibLSBI.ttf`
5. Select the extracted `.ttf` files, right-click, and choose **Install**.
6. Close and reopen your PDF reader.
7. If the PDF reader still reports a missing font, restart Windows so the font cache is refreshed.

## Notes

This README does not redistribute the font files. It points to the official Logos-hosted installer that contains them.
