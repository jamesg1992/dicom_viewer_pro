# DICOM Viewer Pro

[![Release](https://img.shields.io/badge/release-v1.0.0-2ea44f?logo=github)](https://github.com/jamesg1992/dicom_viewer_pro/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-0078d7?logo=windows)](https://github.com/jamesg1992/dicom_viewer_pro/releases)
[![Python](https://img.shields.io/badge/python-3.13-blue?logo=python)](https://www.python.org)
[![License](https://img.shields.io/badge/license-MIT-lightgrey?logo=opensource)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/jamesg1992/dicom_viewer_pro?logo=git)](https://github.com/jamesg1992/dicom_viewer_pro)

Modern DICOM viewer for Windows with a clean interface, advanced filters, thumbnails, measurements, and JPG/DICOM/PDF exports.

## Download
Download the Windows executable from the **Releases** page of this repository.

## Features
- Open single DICOM files, folders, and ZIP archives
- Thumbnail previews in the file list
- Filters by patient name, ID, study period, and modality (CT, MR, CR, DR, US, etc.)
- Distance and area measurements (with mm support via PixelSpacing)
- Exports: JPG, DICOM, and PDF (with metadata + image)

## Installation
1. Download the latest release from the **Releases** page.
2. Place the executable in any folder (e.g. `C:\Program Files\DICOM Viewer Pro\`).
3. Double-click to run.

No installation required — pure portable executable.

Optional: associate `.dcm` files with the app via the installer (if using the Inno Setup version).

## Quick Usage Guide
- **Left mouse**: pan image
- **Mouse wheel**: zoom in/out
- **Right mouse**: windowing (WW/WC)
- **Measurements**: select "Distanza" or "Area rettangolo" from menu, then drag on image

## Technical Notes
- Built with Python 3.13
- Uses: pydicom, customtkinter, Pillow, numpy, fpdf2
- Single-file Windows executable via PyInstaller (`--onefile`)

## Roadmap

### Next Features
- [ ] Multi-slice / multi-frame navigation (CT/MR series)
- [ ] Annotations and text overlays
- [ ] Save measurements with images
- [ ] Smooth animations and transitions
- [ ] Dark/light theme switch
- [ ] History of opened files
- [ ] Export to PNG with annotations

### Future Enhancements
- DICOM RT structure support
- Network DICOM (DICOMweb)
- Plugin system for custom filters
- Mobile viewer companion app

## Reporting Issues
Open an issue if you find bugs or want to suggest improvements.

## License
Open source project under the MIT License. See the `LICENSE` file in this repository.

## Acknowledgments
Built with open source components:
- Python
- pydicom
- customtkinter
- Pillow
- numpy
- fpdf2
