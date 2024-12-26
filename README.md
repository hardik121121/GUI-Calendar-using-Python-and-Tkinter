# 📅 GUI Calendar Application

Welcome to the **GUI Calendar Application**! 🎉 This Python-based project uses the Tkinter library to create an interactive and user-friendly calendar viewer. Whether you're exploring Python GUI development or need a functional calendar tool, this project is perfect for you! 🚀

## 🌟 Features
- **User-Friendly Interface**: Intuitive design for effortless interaction.
- **Dynamic Year Input**: Enter any year to view its complete calendar.
- **Elegant Design**: Appealing colors and fonts enhance the experience.
- **Interactive Calendar Viewer**: Displays the full calendar in a secondary window.

## 🛠️ Built With
- **[Tkinter](https://docs.python.org/3/library/tkinter.html)**: Python’s standard library for creating graphical user interfaces.
- **[Calendar Module](https://docs.python.org/3/library/calendar.html)**: Used to generate the year’s calendar.

## 🔍 Code Walkthrough

### Root Window
The application starts with a root window named **GUI Calendar**:
- A label titled **Calendar**.
- A prompt to "Enter the year."
- An entry box to input the desired year.
- A button labeled **Show Calendar!**, which opens the yearly calendar viewer.

### Calendar Viewer
When the "Show Calendar!" button is clicked:
1. A new window opens with the title **Complete year calendar**.
2. The entered year is processed using the `calendar.calendar()` function to generate the full calendar.
3. The output is displayed in the window using a `Label` widget.

## 🎨 Design Highlights
- **Color Scheme**: 
  - Root Window: `gray` background for a neutral look.
  - Calendar Viewer Window: `Light pink` background for a cheerful touch.
- **Font Styling**: Bold, readable fonts with `Arial` typeface.
- **Responsive Layout**: Widgets arranged with the `grid` layout for clarity.

## ▶️ How to Use
1. Ensure Python is installed on your system. 🐍
2. Save the code in a file named `gui_calendar.py`.
3. Run the script via your Python IDE or terminal:
   ```bash
   python gui_calendar.py
   ```
4. Enter the desired year and click **Show Calendar!** to view the complete calendar.


## 🙌 Contributing
Feel free to fork this repository and contribute by submitting pull requests. Suggestions and improvements are always welcome! 💡

## 📃 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Happy coding! 💻✨

