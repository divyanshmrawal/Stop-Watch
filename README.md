<h1>Stopwatch in Java</h1> <h2>Overview:</h2> <p>This project is a simple, console-based Stopwatch application developed using Java. The stopwatch allows users to start, stop, reset, and display the elapsed time. It provides basic functionality to measure the time between two events, displaying the time in hours, minutes, seconds, and milliseconds. The user interacts with the stopwatch through a text-based menu in the console.</p> <h2>Key Features:</h2> <h3>Time Tracking:</h3> <ul> <li>The stopwatch tracks time in milliseconds and can display the elapsed time in hours, minutes, seconds, and milliseconds format.</li> <li>It uses <code>System.currentTimeMillis()</code> to calculate elapsed time, capturing the difference between the time when the stopwatch was started and the current system time.</li> <li>It continuously tracks time while the stopwatch is running and updates the displayed time in real-time.</li> </ul> <h3>User Controls:</h3> <h4>Start:</h4> <ul> <li>Users can start the stopwatch by selecting the "Start" option from the menu.</li> <li>The stopwatch begins counting from zero and tracks time until stopped.</li> </ul> <h4>Stop:</h4> <ul> <li>Users can stop the stopwatch at any time, and the current elapsed time will be displayed in hours, minutes, seconds, and milliseconds format.</li> <li>Once stopped, the user has the option to reset or restart the stopwatch.</li> </ul> <h4>Reset:</h4> <ul> <li>Users can reset the stopwatch, which will clear the current elapsed time and set the stopwatch back to zero.</li> </ul> <h4>Display Time:</h4> <ul> <li>The program displays the elapsed time in the format of HH:MM:SS.mmm (hours, minutes, seconds, and milliseconds) when the user selects the option to view the time.</li> </ul> <h3>Game Logic:</h3> <h4>Elapsed Time:</h4> <ul> <li>The stopwatch tracks time from the moment it is started, updating the time every millisecond.</li> <li>After starting the stopwatch, users can stop, reset, or view the current time at any point.</li> </ul> <h4>Displaying Time:</h4> <ul> <li>The time is displayed in a clear and readable format: <strong>HH:MM:SS.mmm</strong> (hours, minutes, seconds, and milliseconds).</li> <li>The program updates the display every second (showing minutes, seconds) and includes milliseconds for precision while the stopwatch is running.</li> </ul> <h3>Input Validation:</h3> <ul> <li>The program ensures that user input is valid for each menu option, such as selecting "Start", "Stop", "Reset", or "Display Time".</li> <li>If the user inputs an invalid option, the program will prompt them to try again.</li> </ul> <h2>Technologies:</h2> <h3>Java:</h3> <ul> <li>The application utilizes core Java libraries such as <code>System.currentTimeMillis()</code> for time tracking and <code>Scanner</code> for accepting user input.</li> <li>It uses basic control flow (if-else statements) and loops to create a user-interactive experience for the stopwatch.</li> </ul> <h3>Object-Oriented Programming (OOP):</h3> <ul> <li>The Stopwatch program is implemented using key Object-Oriented Programming (OOP) principles such as Encapsulation (encapsulating the time-tracking logic in a Stopwatch class) and Abstraction (providing a user-friendly interface while hiding implementation details).</li> <li>The application could be further extended with OOP features, such as inheritance, if additional features (like a lap timer) were added.</li> </ul> <h2>How to Use:</h2> <ol> <li>Start the stopwatch by running the <code>Stopwatch.java</code> file in your Java IDE or console.</li> <li>The program will present a text-based menu with the following options: <ul> <li><strong>Start</strong> – Begins the stopwatch.</li> <li><strong>Stop</strong> – Stops the stopwatch and displays the current elapsed time.</li> <li><strong>Reset</strong> – Resets the stopwatch back to 00:00:00.000.</li> <li><strong>Display Time</strong> – Shows the elapsed time in the HH:MM:SS.mmm format.</li> <li><strong>Exit</strong> – Exits the application.</li> </ul> </li> <li>To display the time, you can select "Display Time" at any point after starting or stopping the stopwatch.</li> <li>Users can stop the stopwatch, reset it, or restart it as needed.</li> </ol> <h2>How to Run:</h2> <ol> <li>Clone this repository to your local machine or create a new project in your favorite Java IDE (e.g., Eclipse, IntelliJ, NetBeans).</li> <li>Copy the Java code into a new file named <code>Stopwatch.java</code>.</li> <li>Compile and run the <code>Stopwatch.java</code> file to start the stopwatch application.</li> </ol> <h2>Screenshots:</h2> <img src="https://codewithrandom.com/wp-content/uploads/2022/12/button-.png" alt="Stopwatch Application Screenshot" width="600" />
