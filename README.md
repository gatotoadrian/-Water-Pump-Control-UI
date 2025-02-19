# Water Pump Control UI

This project provides a simple web-based user interface for controlling a water pump remotely using its IP address. The interface allows users to turn the pump on and off with the click of a button.

## Features

- Input field for pump IP address
- Buttons to turn the pump on and off
- Real-time status display
- Responsive design for various screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

## Setup and Usage

1. Clone the repository:
2.  Navigate to the project directory:
3. Open the `index.html` file in a web browser.

4. Enter the IP address of your water pump in the input field.

5. Use the "Turn On" and "Turn Off" buttons to control the pump.

## How It Works

The UI sends HTTP GET requests to the specified IP address with `/on` or `/off` endpoints. The pump's control system should be set up to respond to these requests appropriately.

For example:
- Turning on: `http://<pump-ip-address>/on`
- Turning off: `http://<pump-ip-address>/off`

The status of the pump is updated based on the response received from these requests.

## Customization

You can easily customize the appearance of the UI by modifying the CSS in the `<style>` section of the HTML file.

## Security Considerations

This is a basic implementation and does not include authentication or encryption. For production use, consider adding:

- HTTPS support
- User authentication
- Input validation
- Error handling

## Compatibility

This UI is designed to work with modern web browsers that support ES6+ JavaScript.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/water-pump-control-ui/issues) if you want to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- This project is for educational purposes and should be adapted for real-world use with proper security measures.
- Inspired by IoT control systems and the need for simple, accessible interfaces for home automation.
