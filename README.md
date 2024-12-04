<head>
  <h1>Trigg Console Assembly Guide</h1>
</head>
<body>
  <h2>Introduction</h2>
  <p>
    Welcome to the Trigg Console assembly guide! This project is perfect for hobbyists and enthusiasts who enjoy working with electronic components. 
    Follow this step-by-step guide carefully to build your console. Make sure all components are accounted for and organized before starting. 
    Soldering is required for this project, so basic soldering skills are necessary. If you're new to soldering, we are here to support you.
  </p>
  <img 
        src="image/IMG_2681.jpg" 
        alt="Second batch of components" 
        width="400" 
        height="500">
  <h2>How to Start</h2>
 <p>
    To ensure a smooth assembly process, sort your components into two groups: one for the first stage and another for the second stage of assembly. 
    Work on a clean, well-lit surface to avoid losing any small parts. Have a soldering iron, solder, and tools like wire cutters and tweezers ready.
    A damp sponge or brass wire cleaner will also be helpful to keep your soldering iron tip clean.
  </p>
  <h2>List of Components</h2>
  <div>
    <div>
      <img 
        src="image/IMG_2682.jpg" 
        alt="First batch of components" 
        width="400" 
       height="500">
      <ul>
        <li>Display module.</li>
        <li>Push buttons (8 units).</li>
        <li>LEDs (2 yellow LEDs).</li>
        <li>Pin headers (8-pin and 4-pin female headers).</li>
        <li>Pin headers (4-pin male headers).</li>
        <li>Ceramic capacitors (2 small yellow components).</li>
        <li>Resistors (4 units).</li>
        <li>Toggle switch (1 small slide switch).</li>
      </ul>
    </div>
    <div>
      <img 
        src="image/IMG_2683.jpg" 
        alt="Second batch of components" 
        width="400" 
        height="500">
      <ul>
        <li>Small speaker (1 unit, with a red-and-black wire)</li>
        <li>Plastic mount (for batteries)</li>
        <li>Sound board (inside the small anti-static bag)</li>
        <li>Raspberry Pi Pico board (green microcontroller board)</li>
        <li>2 Pin headers (20-pin male headers)</li>
        <li>3 Pin headers (20-pin and 7-pin female headers)</li>
      </ul>
    </div>
  </div>

  <h2>Step by Step</h2>
  <ol>
    <li>
      <strong>Prepare your workspace:</strong> Clear your workspace and organize the components into two groups as shown above. 
      Ensure you have all the necessary tools: a soldering iron, solder, wire cutters, a damp sponge and a brass wire cleaner. 
      Plug in your soldering iron and let it heat up to the appropriate temperature (usually 300–350°C for most projects).
    </li>
    <li>
      <strong>Assemble and solder the display module:</strong> 
      - Insert the 8-pin and 4-pin female headers into their designated positions on the PCB. Hold them in place with tape or a temporary holder.
      - Flip the board over and solder each pin securely to the PCB. Ensure the solder forms a clean, cone-shaped joint around the pin.
      - Check for any solder bridges (accidental connections between pins) and correct them using a solder wick if necessary.
    </li>
    <li>
      <strong>Install and solder the buttons:</strong> 
      - Place the 8 push buttons into their corresponding slots on the PCB. Ensure they are aligned correctly.
      - Solder the pins of each button to the board. Apply just enough solder to cover the pad without spilling over.
    </li>
    <li>
      <strong>Attach and solder the LEDs and resistors:</strong> 
      - Insert the 2 yellow LEDs into their positions, ensuring the longer leg (positive) goes into the hole marked with a "+" sign.
      - Place the 4 resistors in their respective slots. If the resistors have color bands, follow the provided schematic for correct placement.
      - Solder all leads to the PCB and trim any excess wire sticking out using wire cutters.
    </li>
    <li>
      <strong>Mount and solder the toggle switch:</strong> 
      - Place the toggle switch into its slot on the board. Ensure it is flush with the PCB surface.
      - Solder the switch terminals securely. Avoid overheating the switch by working quickly and efficiently.
    </li>
    <li>
      <strong>Connect and solder the sound board and speaker:</strong> 
      - Carefully remove the sound board from its anti-static bag and align it with the designated area on the PCB.
      - Solder the sound board's pins, ensuring stable connections.
      - Attach the small speaker wires to their respective terminals and solder them in place. Double-check the polarity if indicated.
    </li>
    <li>
      <strong>Install and solder the Raspberry Pi Pico:</strong> 
      - Solder the 20-pin male headers to the Raspberry Pi Pico board first. Ensure each pin is properly soldered.
      - Once the headers are attached, insert the Raspberry Pi Pico into the female headers on the main PCB and secure it in place.
    </li>
    <li>
      <strong>Attach the battery mount:</strong> 
      - Secure the plastic battery mount to the bottom of the PCB using screws or adhesive, depending on the design. 
      - Route the battery wires carefully to avoid tangles or interference with other components.
    </li>
    <li>
      <strong>Final assembly:</strong> 
      - Double-check all soldered connections for stability and ensure no joints are "cold" (dull or crumbly solder).
      - Use a multimeter to test continuity and check for short circuits.
      - Insert the batteries, power on the console, and test its functionality.
    </li>
  </ol>

  <h2>Conclusion</h2>
  <img 
        src="image/IMG_2684.jpg" 
        alt="Second batch of components" 
        width="400" 
        height="500">
  <img 
        src="image/IMG_2685.jpg" 
        alt="Second batch of components" 
        width="400" 
        height="500">
  <p>
    Congratulations on completing your Trigg Console! If you encounter any issues, review each step and check for loose or improperly soldered connections. 
    This project is a great starting point for experimenting with electronics, so feel free to customize and expand its functionality. Enjoy!
  </p>
</body>
</html>
