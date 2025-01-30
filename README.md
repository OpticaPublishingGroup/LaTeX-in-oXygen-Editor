<a id="readme-top"></a>
# LaTeX in oXygen Editor

## About The Project

This repository contains code and instructions for rendering and editing LaTeX equations in the Author mode of [oXygen XML Editor](https://www.oxygenxml.com/) desktop edition. 
To use the code, you must have access to a [MathJax](https://www.mathjax.org/) web service configured to accept LaTeX code as a parameter and return an SVG file showing the rendered math. 
See the following references for setting up such a service: [MathJax web hosting](https://docs.mathjax.org/en/latest/web/hosting.html),  [MathJax general documentation](https://docs.mathjax.org/en/latest/)

Provided in this repository are CSS commands that use custom oXygen functions and Javascript to do two things: 
1. Send LaTeX equations to a MathJax service to return an SVG rendering to the oXygen XML Editor Author environment
2. Create a convenient editing interface for LaTeX equations for the Author environment

The CSS file uses custom functions from the following resource and is configured to obtain math from the XML tag &lt;tex-math&gt;:
[oXygen CSS functions](https://www.oxygenxml.com/doc/versions/27.0/ug-editor/topics/dg-oxygen-css-functions.html). 

![oxygen-math-editor](https://github.com/user-attachments/assets/01d26ef7-17ac-4d2f-abb4-59846fc191f8 "LaTeX in oXygen showing MathJax display (left) and code editor (right)")
View in oXygen Editor Author mode. Code editor is invoked by clicking on icon as shown. Image from Srivallapanondh S., et al. , Opt. Express, **33,** 2558 (2025), [10​.1364/OE.542061](http://dx.doi.org/10.1364/OE.542061).


## Prerequisites

* oXygen XML Editor and a suitable oXygen framework (the CSS must be used within a compatible [oXygen framework directory](https://www.oxygenxml.com/doc/versions/27.0/ug-editor/topics/selecting-combining-multiple-css-styles.html)).
* Access to a MathJax service as described above.

## License

Distributed under the project_license. See `LICENSE.txt` for more information.

## Contact

pubsquestions@optica.org
