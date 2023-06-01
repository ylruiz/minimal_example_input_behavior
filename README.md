# input_in_selection_area

Minimal example to reproduce a strange behaviour with the input when they are within a SelectionArea widget.

- If you run the project using v3.3.x users will be able to type in the input without any issues.
- If you run the project using v3.7.x or v3.10.2 users are **NOT** able to type in the inputs anymore.

This happens when we open the url within our **_mobile browser_**. In desktop browsers, it works as expected.

## Getting Started

1. Find out what is your network IP address.

2. Run the app using the following command

`flutter run -d web-server --web-port (port) --web-hostname (network-ip-address)`

3. Hit the link http://(network-ip-address):(port) which should open the app


**NOTE**: Please, be sure you are using the right version of Flutter in order to reproduce the error since it works find with  v3.3.x but it doesn't work as expected when using v3.7.x or v3.10.2  