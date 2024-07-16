# Dynamic Link for Exciting a 1x2 Array of Edge-Fed Rectangular Patch Antennas

In antenna arrays, a dynamic link or feed network is used to distribute the input signal to multiple antenna elements. For a 1x2 array of edge-fed rectangular patch antennas, the dynamic link typically involves a power divider network that ensures proper phase and amplitude distribution to each antenna element.

## How a Dynamic Link Works

### 1. Power Divider Network
The power divider is a crucial component that splits the input signal into two equal parts with minimal loss. In a simple 1x2 array, a Wilkinson power divider or a T-junction power divider can be used.

#### Wilkinson Power Divider
- **Structure**: It consists of two quarter-wavelength transmission lines and a resistor connected between the output ports to ensure impedance matching and isolation.
- **Function**: It equally splits the input power into two output ports with a 3 dB loss due to the splitting. The resistor ensures that any reflected power from the antenna elements is absorbed, minimizing mutual coupling.

#### T-Junction Power Divider
- **Structure**: A simpler structure where a transmission line branches out into two paths.
- **Function**: It also splits the power but may have less isolation and higher loss compared to a Wilkinson divider.

### 2. Transmission Lines
After the power is divided, transmission lines are used to feed the power to each patch antenna. The length of these lines is crucial for maintaining the correct phase relationship between the antennas, especially if they are intended to operate in-phase.

### 3. Impedance Matching
To ensure maximum power transfer and minimize reflections, impedance matching is essential. This is often achieved by using quarter-wave transformers or matching stubs.

### 4. Excitation of Patch Antennas
Each patch antenna is edge-fed, meaning the feed point is located at the edge of the patch. The edge feed is chosen to match the input impedance of the patch antenna, typically 50 ohms. Proper excitation ensures that each patch radiates efficiently and in the desired pattern.

### 5. Dynamic Behavior
The term "dynamic link" implies that the feeding network can adapt to changes in the operating conditions, such as frequency, load impedance, or even environmental factors. In more advanced systems, this could involve electronically tunable components like varactors or MEMS switches to adjust the impedance matching or phase shifting dynamically.

By properly designing the dynamic link, the 1x2 array can achieve efficient radiation patterns, good impedance matching, and minimal mutual coupling between the patches, leading to better overall performance.
