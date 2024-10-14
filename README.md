# Browser Application

This project is a basic web browser application built using JavaFX. It provides a tabbed browsing experience with navigation controls.
![image](https://github.com/user-attachments/assets/b12a689f-807a-44c1-a2bc-dfacb0d4ba33)


## Project Structure

The project consists of four main Java classes:

1. `BrowserLauncher.java`: The entry point of the application.
2. `WebBrowserApp.java`: The main application class that sets up the browser window and tab management.
3. `WebPageView.java`: Represents a single browser tab with web view and navigation controls.
4. `IconButton.java`: A custom button class for creating buttons with images.
5. `BrowserStyles`: For styling of elements via css.

## Features

- Tabbed browsing interface
- Navigation controls (Back, Forward, Reload)
- URL input field
- Progress bar for page loading
- Ability to add new tabs

## Requirements

- Java Runtime Environment (JRE) 8 or higher
- JavaFX library (included in JRE 8, may need to be added separately for later versions)

## How to Run

### Using the JAR file

1. Ensure you have Java installed on your system.
2. Double-click the provided JAR file to run the application.

Alternatively, you can run it from the command line:

```
java -jar BrowserFX.jar
```

### From Source Code

If you want to compile and run from source:

1. Ensure you have JDK installed on your system.
2. Compile the Java files:
   ```
   javac application/*.java
   ```
3. Run the application:
   ```
   java application.Main
   ```

## Screenshots

Screenshots of the running application are included in the project directory. These provide a visual reference for the application's interface and functionality.

## Class Descriptions

### Main.java

This class serves as the entry point for the application. It calls the `main` method of the `Browser` class.

### Browser.java

The `Browser` class extends JavaFX's `Application` class and sets up the main window of the browser. It creates a `TabPane` to manage multiple tabs and provides a button to add new tabs.

### SinglePage.java

`WebPageView` represents an individual browser tab. It includes:
- A `WebView` for rendering web pages
- Navigation controls (Back, Forward, Reload buttons)
- A URL text field
- A progress bar for page loading

### ImageButton.java

A custom `Button` class that creates buttons with images. It provides visual feedback when pressed.
