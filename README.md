# Windows Program with Loop and Window Management

This C++ program is designed to run a loop while managing the visibility of the current foreground window. It demonstrates how to hide the current program from the taskbar, run a loop, and open specific system files.

## Prerequisites

To run this program, you need the following:

1. A Windows operating system.
2. The `error.vbs` and `dir.exe` files should be present within the program's directory.

## Usage

1. Clone or download this repository to your local machine.

2. Ensure that `error.vbs` and `dir.exe` are available in the program's directory.

3. Compile and run the program using a C++ compiler, such as [MinGW](http://www.mingw.org/) or [Visual Studio](https://visualstudio.microsoft.com/).

4. When the program is executed, it will:

   - Set the console text color to green on a black background.
   - Instruct the user not to press Enter.
   - Run a loop according to the specified count (default is 50).
   - In each iteration of the loop, it will:
     - Hide the current program from the taskbar.
     - Open `error.vbs`.
     - Open `cmd.exe`.
     - Open `dir.exe`.
     - Optionally, open `explorer.exe` every other iteration.
     - Display the progress of the loop.

5. After the loop is completed, the foreground window will be restored.

## Important Note

This program makes changes to window visibility and runs system files. Be cautious when using it and ensure it is not mistaken for malicious activity. It is recommended to use this program in a controlled environment.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to modify this README as needed and include additional details or warnings specific to your use case. Additionally, you may want to provide more details about what the `error.vbs` and `dir.exe` files are and their intended purpose.
