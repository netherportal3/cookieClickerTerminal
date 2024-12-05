### README: Cookie Clicker Terminal Edition

---

## **About the Game**
Cookie Clicker Terminal Edition is a text-based incremental game where you:
- Click (`C`) to earn cookies.
- Use cookies to buy buildings (`B`) to increase Cookies Per Second (CPS).
- Upgrade (`U`) and rebirth (`R`) to improve your efficiency.
- Unlock achievements (`A`) as you progress!

Your goal is to bake as many cookies as possible while enjoying the simplicity of this terminal-based game.

---

## **Help / Instructions**
### Commands:
| Command | Action                                              |
|---------|-----------------------------------------------------|
| `C`     | Click to earn cookies.                             |
| `B`     | Open the buildings menu to buy production buildings.|
| `U`     | Open the upgrades menu.                            |
| `R`     | Rebirth (prestige) for permanent CPS bonuses.       |
| `A`     | View unlocked achievements.                        |
| `Q`     | Quit the game.                                      |

---

## **Compiling and Running the Game**

### **Using g++**
1. Ensure you have `g++` installed. On Linux/Unix, you can install it via:
   ```bash
   sudo apt-get install g++
   ```
2. Compile the game using:
   ```bash
   g++ main.cpp functions.cpp -o game -pthread
   ```
3. Run the game:
   ```bash
   ./game
   ```

---

### **Using Visual Studio**
1. Open Visual Studio and create a new C++ project.
2. Add `main.cpp` and `functions.cpp` to your project.
3. Build the project:
   - Go to **Build > Build Solution** (or press `Ctrl+Shift+B`).
4. Run the game:
   - Press `Ctrl+F5` to execute the program without debugging.

---

### **Using Other IDEs**
#### **CLion** (CMake-based):
1. Open the project folder in CLion.
2. Ensure `CMakeLists.txt` includes:
   ```cmake
   add_executable(game main.cpp functions.cpp)
   ```
3. Click **Build** and then **Run**.

#### **Code::Blocks**:
1. Create a new C++ project and add the `.cpp` files to your project.
2. Build the project using the **Build** menu.
3. Run the program.

---

## **Contributing**
Feel free to fork this project and submit pull requests with new features or bug fixes!
I wrote this for my c++ intro class, all credit to Orteil's Cookie Clicker for the idea!
---
