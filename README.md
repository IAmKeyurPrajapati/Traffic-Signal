# Traffic Signal Simulation

This project is a web-based simulation of a traffic signal system. The user can define custom sequences and intervals for each signal light and control the sequence using "Start" and "Stop" buttons.

## Features

- **Customizable Signal Sequence**: The user can assign custom order values to signals A, B, C, and D to determine the sequence in which they light up.
- **Customizable Time Intervals**: The user can define separate intervals (in seconds) for how long the lights should stay green and yellow for each signal.
- **Start and Stop Controls**: The simulation allows users to start the traffic light sequence and stop it when needed.
- **Dynamic Button Text**: The "Start" button text changes to "Stop" when the simulation is running.

## Technologies Used

- **HTML/CSS**: For the layout and styling of the signals, input fields, and buttons.
- **JavaScript (jQuery)**: For the dynamic behavior of the signals, sequence handling, and button state management.

## How It Works

1. **Define the Sequence**: Enter numbers in the input fields next to signals A, B, C, and D to set the sequence order (e.g., 1 for A, 2 for B, etc.).
2. **Set Time Intervals**: Enter the green and yellow time intervals (in seconds) for how long each signal should be active.
3. **Start the Sequence**: Click the "Start" button to begin the signal sequence. The signals will light up according to the defined order and intervals.
4. **Stop the Sequence**: Use the "Stop" button to end the sequence at any time.

## Usage

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Set the desired sequence and interval values and press "Start" to see the simulation in action.

## Example

- **Sequence**: A: 1, B: 2, C: 3, D: 4
- **Green Interval**: 5 seconds
- **Yellow Interval**: 2 seconds

When the "Start" button is clicked, Signal A will turn green for 5 seconds, followed by turning yellow for 2 seconds, and then move on to Signal B, and so on.

## License

This project is licensed under the MIT License.
