# PoC for jQuery Vulnerability

This project demonstrates a Proof of Concept (PoC) for a Cross-Site Scripting (XSS) vulnerability that can occur when using a vulnerable version of the jQuery library. The example highlights the risks associated with directly assigning user-controlled data to `innerHTML` and using older, vulnerable versions of jQuery.

## Description

This PoC is designed to showcase how an attacker might exploit a vulnerability in a web application that uses jQuery version 1.6.4. The example demonstrates how an XSS attack can be triggered by injecting a malicious payload into the DOM via `innerHTML`, leading to the execution of arbitrary JavaScript code.

## Setup

To run this PoC, simply open the `index.html` file in your browser. The file includes the vulnerable jQuery version and a script that injects a payload into a div element, triggering an XSS alert.

## Disclaimer

This PoC is intended for educational purposes only. The use of outdated and vulnerable libraries in production environments is strongly discouraged. Always ensure that you are using the latest, secure versions of any dependencies in your projects.

## Files

- `index.html`: The main HTML file containing the PoC code.
- `README.md`: This file, providing an overview of the project and its purpose.


