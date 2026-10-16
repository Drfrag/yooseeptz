## Disclaimer

**This project includes a compatibility fix for Home Assistant service calls, allowing camera entities to be selected using `entity_id` when `device_id` is not provided.**

The changes were tested with three Yoosee cameras in a Home Assistant environment. PTZ controls were confirmed to work independently for each camera when the correct camera entity is selected.

However, compatibility may vary depending on the camera model, firmware, and network configuration. I cannot guarantee that this component will work with every Yoosee or GWIPC camera.

If you encounter issues, please open an issue and include your camera model, firmware version, connection details (TCP or other protocol), and relevant logs, while removing any passwords or other sensitive information.

This project is based on the original work available at https://github.com/carvalr/PTZ-YALL, with subsequent modifications from https://github.com/RICARDOKR/yooseeptz.
