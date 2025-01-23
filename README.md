<a id="readme-top"></a>
# LaTeX in oXygen Editor

## About The Project

This repository contains code and instructions for rendering and editing LaTeX equations in the Author mode of oXygen XML Editor desktop edition. 
To use the code, you must have access to a MathJax web service configured to accept LaTeX code as a parameter and return an SVG file showing the rendered math. 
See the following references for setting up such a service: 
*[MathJax web hosting](https://docs.mathjax.org/en/latest/web/hosting.html)
*[MathJax general documentation](https://docs.mathjax.org/en/latest/)

Provided in this repository are CSS commands that use custom oXygen functions and Javascript to do two things: 
1. Send LaTeX equations to a MathJax service to return an SVG rendering to the oXygen XML Editor Author environment
2. Create a convenient editing interface for LaTeX equations for the Author environment

The CSS file uses custom functions from the following resource and is configured to obtain math from the XML tag &lt;tex-math&gt;:
[oXygen CSS functions](https://www.oxygenxml.com/doc/versions/27.0/ug-editor/topics/dg-oxygen-css-functions.html). 

## Prerequisites

* oXygen XML Editor and a suitable oXygen framework (the CSS must be used within a compatible [oXygen framework directory](https://www.oxygenxml.com/doc/versions/27.0/ug-editor/topics/selecting-combining-multiple-css-styles.html)).
* Access to a MathJax service as described above.

## License

Distributed under the project_license. See `LICENSE.txt` for more information.

## Contact

custserv@optica.org
