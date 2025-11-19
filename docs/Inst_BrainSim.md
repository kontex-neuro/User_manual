
---

<br><br><br>

![test1](<DDS user manual-01.png>)

<br><br><br><br><br><br>

### **Overview**

<div class="text-block">
    <p>The BrainWave Simulator is a precision signal-generation platform designed to emulate neural activity for end-to-end validation and calibration of neural acquisition systems—from electrodes and headstages to acquisition platforms (e.g., XDAQ and others) and integrated experimental I/O setups. Its compact form factor, battery-powered operation, and dual-channel programmable outputs provide researchers with a reliable solution for bench-top testing and in-lab system verification—without the need for live tissue samples or biological inputs.</p> 
    As part of our continuous product enhancement strategy, the BrainWave Simulator has been refined to incorporate expanded signal source options, improved electrical integration, and streamlined control features. These improvements are evolutionary rather than disruptive, ensuring that all devices retain full compatibility with existing workflows while extending their applicability to more advanced experimental paradigms.
    </div>

<br>

![test1](<DDS user manual-02.png>)

<br><br><br><br><br><br>

### **Components**

<br>

![test1](<DDS user manual-03.png>)

<br><br><br><br><br><br>

### **Dimension And Weight**

![test1](<DDS user manual-04.png>)

<div class="text-block2">
    <p align="right">Weight ~260g</p>
    <p align="right">unit: mm</p>
</div>

<br><br><br><br><br><br>

### **Key Features**

<div class="text-block">
    <h4> Purpose-Built for Validating Neural Acquisition Pipelines</h4> 
    <ul>
    <Li> Compatible with KonteX X-Headstages and other headstage systems</Li>
    <Li> Enables full pipeline testing using electrodes in PBS</Li>
    </ul>
    <h4> Dual-Channel, Fully Programmable Signal Output</h4>
    <ul> 
    <Li> Two independent output channels, each configurable with discrete amplitude and frequency settings</Li>
    <Li> Enhanced signal source architecture: selectable onboard signal generator or external source</Li>
    <Li> Amplitude options:</Li>
    <p>- Onboard waveform mode:</p>
    3mV, 0.5mV, 0.1mV, or 0mV(mute) to accommodate a wide range of headstage sensitivity requirements.
    <p>- External signal mode:</p>
    Divide external signal by: 1,000, 6,000, 30,000, and 0V(off)
    <Li> Frequency options:</Li>
    <p>- Onboard waveform mode:</p>
    1000 Hz, 500 Hz, 30 Hz, 10 Hz selected for common neural signal validation bandwidths.
    <p>- External signal mode: </p>
    Integrate filter circuit for common neural signal frequency range from 75Hz to 5KHz.
    <Li>Independent channel configuration ensures channel-isolated testing and headstage characterization.</Li>
    </ul>
</div>

<div class="text-block">
    <h4> Multiple Waveform Profiles for Comprehensive Testing </h4>
    <ul>
    <Li><strong>Sine wave:</strong>
    For baseline gain and frequency response measurements.</Li>
    <Li><strong>Square wave:</strong>
    For slew rate and transient response testing.</Li>
    <Li><strong>Triangle wave:</strong>For linearity and Tsymmetry verification.</Li>
    <Li><strong>Simulation (Sim) mode:</strong>Synthetic waveform featuring a parameter-adjustable carrier with randomized spike patterns designed to approximate biological neural signals for realistic validation.</Li>
    </ul>
</div>

<div class="text-block">
    <h4> Integrated TTL Synchronization Output </h4>
    <ul>
    <Li>3.3 V logic-level pulse output operates in a push (High) and release (Low) manner.</Li>
    <Li>Standard 3.5 mm to BNC cable interface for straightforward connection to downstream acquisition or stimulation devices.</Li>
    <Li>Ideal for time-locking signal generation to data collection or closed-loop feedback systems.</Li>
    </ul>
</div>

<div class="text-block">
    <h4> Battery-Powered Low-Noise Operation </h4>
    <ul>
    <Li>Internal rechargeable Li-ion battery delivers approximately 12 hours of continuous use on a full charge.</Li>
    <Li>Charging via USB-C takes 2.5 hours and does not require additional configuration.</Li>
    </ul>
</div>

<br><br><br><br><br><br>

### **Device Overview**

![test1](<DDS user manual-05.png>)

<center><h4>&emsp;Side view &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Front view &emsp;</h4></center>

<br><br><br><br><br><br>

### **LED Indicators**

![test1](<DDS user manual-06.png>)

<br>

<div class="text-block1">
    <h4> Power Indicator LED </h4>
    <ul>
    <Li>Confirms that the BrainWave Simulator is powered on and operating.</Li>
    <Li>Provides immediate visual feedback that the device is active.</Li>
    </ul>
</div>

<div class="text-block1">
    <h4> Battery Status LED </h4>
    <ul>
    <Li>While charging: The indicator light flashes red, indicating that the internal battery is recharging.</Li>
    <Li>Low battery: The indicator light is solid red, alerting the user to recharge the device to maintain uninterrupted operation.</Li>
    <Li>See below for a full explanation of the LED status.</Li>
    </ul>
</div>

<br>

![test1](<DDS user manual-07.png>)

<br><br><br><br><br><br>

### **Testing the Headstage**

<div class="text-block">
    <Li><h4> Attach the X-Headstage™</h4></Li>
    These steps apply to all KonteX X-Headstage™ compatible accessories.
</div>

![test1](<DDS user manual-08-08.png>)

<br>

<div class="text-block">
    <h4> 1. Align the Connectors</h4>
   Carefully align the connectors. When the interface board features an alignment arrow, orient the X-Headstage™ so the micro-HDMI connector matches the arrow's direction.
</div>

![test1](<DDS user manual-9-1.png>)

<br>

<div class="text-block">
    <h4> 2. Press Down Firmly</h4>
   Carefully align the connectors. When the interface board features an alignment arrow, orient the X-Headstage™ so the micro-HDMI connector matches the arrow's direction.
</div>

![test1](<DDS user manual-10-1.png>)

<br>

<div class="text-block">
    <h4> 3. Connect the Micro-HDMI Cable</h4>
   <p>3A. If the X-Headstage™ is attached to a probe adapter designed with a locking mechanism. Secure the connection by locking the screws before plugging in the Micro-HDMI cable.</p>
   3B. Insert the cable while applying even pressure to both the X-Headstage™ and the accessory.<br>
   This minimizes torque to the miniature board-to-board connectors.
</div>

![test1](<DDS user manual-11-1.png>)

<br>

<div class="text-block">
    <h4> 4. Install the Headstage Stabilization Adapter</h4>
   4A: Attach and secure the Headstage Stabilization Adapter by tightening the thumb screws.
</div>

![test1](<DDS user manual-12-1.png>)

<div class="text-block">
   4B: With the assembly secured, push the headstage assembly into the headstage port on the Brainwave Simulator.
</div>

![test1](<DDS user manual-13-1.png>)

<br><br><br>

<div class="text-block">
    <Li><h4> Detach the X-Headstage™</h4></Li>
</div>

![test1](<DDS user manual-14.png>)

<br>

<div class="text-block">
    <h4> 1. Unscrew the thumbscrews to remove the Headstage Stabilization Adapter </h4>
</div>

![test1](<DDS user manual-15.png>)

<br>

<div class="text-block">
    <h4> 2. Disconnect the Micro-HDMI Cable</h4>
   While holding the X-Headstage™ and adapter firmly, gently pull the cable straight back — avoid twisting or lateral force.
</div>

![test1](<DDS user manual-16.png>)

<br>

<div class="text-block">
    <h4> 3. Use the designated XHS tool for detachment </h4>
   Aim the tool tip from the top or bottom, if accessible. <br>
   The XHS tool is purpose-built for X-Headstage™, featuring a single tip for X3-series and a dual tip for X6-series models. Each tip is precision-polished to minimize the risk of damage to PCB surfaces.
</div>

![test1](<DDS user manual-17.png>)

<br>

<div class="text-block5">
    <palign="left"><i># If the XHS tool is unavailable, a flat-head screwdriver with a tip thickness of less than 0.5 mm may be used as an alternative.</i>
</div>

<br>

<div class="text-block">
    <h4> 4. Release and Catch the X-Headstage™ </h4>
   nsert the tool tip at a slight angle into the gap between the X-Headstage™ and its accessory.<br>
   The headstage should release easily with minimal applied force.
</div>

![test1](<DDS user manual-18.png>)

<br>

<div class="text-block">
    <h4> 5. Optional Accessory: Cycle Extender or Remapper </h4>
   Users may consider using this sacrificial interface adapter to reduce wear on the X-Headstage connector from repeated connection cycles and extend its operational lifespan.
</div>

![test1](<DDS user manual-19.png>)

<br><br><br><br><br><br>

### **Configuring Test Waveforms**

<div class="text-block">
    <h4> 1. Power On </h4>
    <ul>
    <Li>Turn on the BrainWave Simulator by sliding the System Mode Switch to ON.</Li>
    <Li>In Onboard waveform mode, the device outputs a 3 mV, 1 kHz sine wave to all channels by default. </Li>
    <Li>In External signal mode, the device configure on divide 1,000 by default.</Li>
    </ul>
</div>

<br>

<div class="text-block">
    <h4> 2. Output Waveform Adjustment </h4>
    The onboard signal generator is capable of producing two independent waveforms—CH1 and CH2—which are alternately assigned across all headstage input channels.
    <ul>
    <Li>Use the CH button to toggle between CH1 and CH2 for configuration.</Li>
    <Li>Adjust the parameters as required using the corresponding control knobs or software interface.</Li>
    </ul>
</div>

<div class="text-block1">
    <strong>Adjustable Parameters: </strong>
    <ul>
    <Li>Amplitude (Amp mV): 3 mV, 500 μV, 100 μV, 0</Li>
    <Li>Frequency (Freq Hz): 1000, 500, 30, 10</Li>
    <Li>Waveform Type (Mode): Sine (Sine), Square (Sq), Triangle (Tri)</Li>
    </ul>
</div>

<div class="text-block1">
    <strong>Simulated (Sim): </strong>
    In Simulated Mode, the generator produces a composite waveform consisting of a carrier sine wave combined with randomly generated spikes.
    <ul>
    <Li>Amplitude (Amp mV): 3 mV, 500 μV, 100 μV, 0</Li>
    <Li>Frequency (Freq Hz): 1000, 500, 30, 10</Li>
    </ul>
</div>

<br>

<div class="text-block">
    <h4> 3. Testing with External Signal Source </h4>
    The BrainWave Simulator accepts external test signal (maximum voltage 2Vrms) via the 3.5 mm stereo jack (e.g. from a PC) and attenuates the signal to appropriate level for headstage or neural probe testing.
    <ul>
    <Li>Sliding the ON/OFF switch to the right.</Li>
    <Li>External signal can be attenuated by:</Li>
    &emsp;-1000 (3mV LED)<br>
    &emsp;-6000 (0.5mV LED)<br>
    &emsp;-30000 (0.1mV LED)<br>
    &emsp;-∞ (muted output: 0mV LED)
    <Li>Upon starup, the device is /1000 by default.</Li>
    <Li>Playing an audio signal on a device enables the BrainWave Simulator to simultaneously generate the corresponding analog output waveform.</Li>
    <Li>Once the headstage is attached on the BrainWave Simulator and connected to XDAQ, the waveform can be directly recorded using the acquisition software.</Li>
    </ul>
</div>

<br>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT :</strong> The peak to peak limited range of the external input should remain below 2Vrms.<br>
    Exceeding this level may cause distortion or permanent damage to the input circuitry.<br>
    For optimal performance, it is recommended to use the headphone output jack of a standard computer as the signal source.
</p>

<br><br><br><br><br><br>

### **Testing with Electrode and Headstage**

<div class="text-block">
    <p>Evaluates electrode or probe performance and system functionality in saline using the BrainWave Simulator before actual recordings.<br><br>
    1.&emsp;Immerse the in-house electrode or Neuropixels probe in the saline bath and connect its headstage to XDAQ.<br>
    2.&emsp;Short the GND/REF of the electrode or Neuropixels and connect them to the GND terminal of the BrainWave Simulator using the saline test adapter with the connector left floating in the air.<br>
    3.&emsp;Immerse the signal electrode from the BrainWave Simulator output channel (CH1 or CH2) into the saline bath to deliver the simulated signal.<br>
    4.&emsp;Adjust the BrainWave Simulator output parameters and observe the signal in the acquisition software. The displayed waveform should change accordingly to the simulator settings.
    </div>

<br>

![test1](<DDS user manual-20.png>)

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT :</strong>  Confirm all connections are correct while applying the signal.<br>
    Ensure a proper grounding and shielding environment to reduce noise and maintain signal stability.
</p>


<br><br><br><br><br><br>

### **Generating a Digital Pulse**

<div class="text-block">
    1.&emsp;Connect a 3.5 mm jack–to–BNC patch cord between the TTL Out port of the BrainWave Simulator and the device receiving the digital pulse (e.g., XDAQ).<br>
    </div>

![test1](<DDS user manual-21.png>)

<div class="text-block">
    2.&emsp;Press the Pulse Trigger button to output a 3.3 V TTL pulse. The signal remains high while the button is pressed and returns low upon release. The pulse frequency depends on the speed of button activation.<br>
    </div>

![test1](<DDS user manual-22.png>)

<div class="text-block">
    3.&emsp;All four frequency indicator LEDs illuminate when the TTL Out signal is at a high logic level.<br>
    </div>

![test1](<DDS user manual-23.png>)

<br><br><br><br><br><br>

### **Connector Specification & Pinout**

<div class="text-block">
    The Brainwave Simulator has undergone several optimizations to provide a reliable connection. The latest design, Version 2, uses a board-to-board connector and enables the use of headstage stabilization adapter.
</div>

<br>

<div class="text-block">
    <h4> Version 2 </h4>
     <ul>
    <Li> Main Connector: 40P 0.8mm Board to Board Mezzanine Connector.</Li>
    </ul>
</div>

![test1](<DDS user manual-24.png>)

<br><br><br><br><br><br>

### **Compatible Accessory**

<div class="text-block">
    <h4> X-Headstage Stabilization Adapter for X3 Headstage (SKU: Adpt-BWS-X3): </h4>
    <ul>
    <Li> This is the default adapter shipped with the Brainwave Simulator.</Li>
    <h4> X-Headstage Stabilization Adapter for X6 Headstage (SKU: Adpt-BWS-X6): </h4>
    <ul>
    <Li> Use this adapter to use with the X6 headstages.</Li>
    </ul>
    <h4> 3.5mm plug to BNC patch cord (SKU: ACC-0007): </h4>
    <ul>
    <Li> Use this patch cord to send a test digital pulse to an instrument.</Li>
    </ul>
    <h4> X-Headstage Remove Tool (SKU: XHS-Tool): </h4>
    <ul>
    <Li> Headstage removal tool.</Li>
    </ul>
    <h4> DDS V1.0 to V2 Adapter (SKU: ACC-0009): </h4>
    <ul>
    <Li> Use this adapter with the v1.0 Brainwave Simulator to use the X3 or X6 Stabilization Adapter.</Li>
    </ul>
    <h4> DDS V1.1 to V2 Adapter (SKU: ACC-0010): </h4>
    <ul>
    <Li> Use this adapter with the v1.1 Brainwave Simulator to use the X3 or X6 Stabilization Adapter.</Li>
    </ul>
    <h4> Adapters to other headstages: </h4>
    <ul>
    <Li> Contact us for customization or use reference Eagle design to modify for your own.</Li>
    </ul>
</div>