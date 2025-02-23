# OpenImageIO muPDF

[OpenImageIO](https://github.com/imageio/imageio) muPDF is an [OpenImageIO](https://github.com/imageio/imageio) plugin for the mupdf library which enables us to read/fetch/view every page in a given PDF file as a ready-to-use image.

## Installation

TBD


## Usage (and Examples)

To use it simply import the library. It will auto-register with ImageIO.


## Why ImageIO muPDF


Having a dedicated repo for the muPDF plugin will eventually allow us to
install the muPDF library at install time, instead of having to ask users to
perform post-install steps to download the library. This might also have
positive implications on platform availability and introspection as we can
eventually compile muPDF while building the package.

