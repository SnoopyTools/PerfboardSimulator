# Gremlin Perfboard Simulator

The **Gremlin Perfboard Simulator** is a lightweight, browser-based prototyping tool designed for hobbyists and electronics enthusiasts. It allows you to plan out physical circuit layouts on standard 0.1" pitch perfboard before touching a soldering iron. By providing synchronized **Top (Placement)** and **Bottom (Solder)** views, the program ensures that your component positions align perfectly with your under-board wiring.

---

## Quick Instruction Guide

### 1. Placing Components
* **Select a Part:** Use the dropdown menu in the sidebar to choose a component (Resistor, LED, Transistor, Wire Link, etc.).
* **Drop on Board:** Click any hole on the **Placement (Top)** board to place the component.
* **Move:** Click a placed component to open the HUD menu and select **Move**, then click a new hole.

### 2. Customizing Parts (HUD Menu)
Clicking any component on the **Top** view opens a floating menu:
* **Value:** Change the resistance, capacitance, or transistor model.
* **Span:** Increase or decrease the distance between the component's pins.
* **Rotate:** Cycle the component through 90-degree rotations.
* **Erase:** Remove the part from the board.

### 3. Wiring & Traces
* **Drawing Traces:** Go to the **Solder (Bottom)** view. Click and drag your mouse between holes to create a continuous solder bridge or wire trace.
* **Deleting Traces:** Click an existing trace on the solder side and select **Erase Trace** from the menu.

### 4. Navigation & Export
* **Active View:** The board you are currently hovering over will be highlighted with a gold border.
* **Saving:** Use the **Save Project** button to download a `.gpf` file. You can reload this file later using **Load Project**.
* **Exporting:** Click **Export SVG** to generate a high-quality image of both sides of your board—complete with the Gremlin watermark—perfect for sharing or printing as a build guide.

---

### Pro Tip
Check the **Solder (Bottom)** view frequently while placing parts. The cyan **Target Rings** show you exactly where the pins of your components are poking through, making it easy to see where you need to start your solder traces!
