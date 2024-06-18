# WorldClock Project

## Overview

The **WorldClock** project is a JavaFX application that displays an analog and digital clock, supporting different time zones and locales. The analog clock is rendered using a custom `ClockPane` component. The application updates the time every second using JavaFX animations.

## Features

- Analog clock display using `ClockPane`.
- Digital clock display with configurable time zone and locale.
- Real-time updates using JavaFX's `Timeline` and `KeyFrame`.

## Installation

1. Ensure you have Java and JavaFX installed.
2. Clone the repository or download the source code.
3. Place the `ClockPane.java` and `WorldClock.java` files in the same directory.

## Usage

1. Compile the Java files:
    ```bash
    javac ClockPane.java
    javac WorldClock.java
    ```

2. Run the `WorldClock` application:
    ```bash
    java WorldClock
    ```

## Classes

### `ClockPane`

A custom JavaFX component that displays an analog clock.

#### Methods
- `ClockPane()`: Constructs a default clock with the current time.
- `ClockPane(int hour, int minute, int second)`: Constructs a clock with specified time.
- `setHour(int hour)`: Sets the hour and repaints the clock.
- `setMinute(int minute)`: Sets the minute and repaints the clock.
- `setSecond(int second)`: Sets the second and repaints the clock.
- `setCurrentTime()`: Sets the current time and repaints the clock.
- `paintClock()`: Paints the clock based on the current time.

### `WorldClock`

Extends `BorderPane` and includes both an analog and digital clock display.

#### Methods
- `WorldClock()`: Initializes the clock displays and starts the real-time updates.
- `setTimeZone(TimeZone timeZone)`: Sets the time zone for the clock.
- `setLocale(Locale locale)`: Sets the locale for the clock.
- `setCurrentTime()`: Updates the analog and digital clocks with the current time.

## Screenshots

(Include any screenshots of your application here)

## Contributing

Contributions are welcome! Please
