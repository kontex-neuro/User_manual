
---

<br><br><br>

![test1](<XDAQ AIO-01.png>)

<br><br><br><br><br><br>

### **Overview**

<div class="text-block">
    <p>The XDAQ™ product line offers a suite of acquisition solutions designed to address the evolving needs of modern neuroscience research. These systems combine flexibility and performance, enabling integrated, multimodal approaches to a wide range of experimental techniques.</p>
    <p>As the top-tier model in the XDAQ series, the AIO sets a new standard for versatility and capability in neuroscience instrumentation, offering robust native support for large-scale neural recording, optogenetic stimulation, and synchronized video acquisition. It supports up to 1024 channels of high-resolution spike recordings and, in XSR mode, provides up to 128 channels that can be dynamically configured for recording or stimulation. It also delivers seamless compatibility with advanced electrode technologies—including Neuropixels probes—with the ability to operate up to four probes simultaneously for high-density, multi-region neural interrogation.</p>
    With its high-bandwidth architecture, extensive I/O options, and precision timing synchronization, the AIO is purpose-built for real-time, closed-loop experiments, multimodal fusion, and large-scale parallel data acquisition across complex behavioral paradigms.
</div>

![test1](<XDAQ AIO-02.png>)

<br><br><br><br><br><br>

### **Components**

<br>

![test1](<XDAQ AIO-03.png>)

<br><br><br><br><br><br>

### **Dimension And Weights**

<br>

![test1](<XDAQ AIO-04.png>)

<div class="text-block2">
    <p align="right">Weight 3050g</p>
    <p align="right">unit: mm</p>
</div>

<br><br><br><br><br><br>

### **Device Overview**

<h4>The AIO Front Panel</h4>

![test1](<XDAQ AIO-05.png>)

<br><br><br>

<h4>The AIO Back Panel</h4>

![test1](<XDAQ AIO-06.png>)

<br><br><br>

<h4>System LED Indicators</h4>

![test1](<XDAQ AIO-07.png>)

<div class="text-block">
    <strong>&#9312; STB LED: </strong>
    Indicates that adequate power is being supplied to the XDAQ™ from the power supply
    <strong>&#9313; ON LED: </strong>
    Indicates that power has been supplied to the system and the system is turned ON.
</div>

<br><br><br>

<h4>XDAQ Mode Indicator</h4>

![test1](<XDAQ AIO-08.png>)

<br>

<h4>XSR Mode VStim Indicator</h4>

![test1](<XDAQ AIO-09.png>)

<br>

<h4>System Status Indicator</h4>

![test1](<XDAQ AIO-10.png>)

<br><br><br><br><br><br>

### **Headstage LED Indicators**

![test1](<XDAQ AIO-11.png>)

<div class="text-block">
    <strong>&#9312; X-Headstage™ Port LED P1 - P4: </strong>
    Indicates that the headstage is properly detected; it will only illuminate after the software initialization is complete.
    <br><br><br>
    <strong>&#9313; Neuropixels Port LED 1 - 4: </strong>
</div>

![test1](<XDAQ AIO-12.png>)

<br><br><br><br><br><br>

### **Setting Up The XDAQ™**

<div class="text-block">
    Connect the DC plug of the supplied power supply, into the power input port.
</div>

<br><br><br>

<div class="text-block">
    <h4>Turning on the XDAQ™</h4>
</div>

![test1](<XDAQ AIO-13.png>)

<div class="text-block">
    <h4>Turning off the XDAQ™</h4>
</div>

![test1](<XDAQ AIO-14.png>)

<br><br><br><br><br><br>

### **Setting Up The IO Ports**

![test1](<XDAQ AIO-15.png>)

<div class="text-block">
    <strong>&#9312; Analog BNC Ports </strong><br>
    AIO features two pairs of wide range (±10V), general purpose 16-bit ADC (AI-01, AI-02) and DAC (AO-01, AO-02) channels, each equipped with a BNC connector for easy access. These ports operate on the same sample rate as the X-Headstage™ (XR, XSR Mode). In NP mode, the sample rate is fixed at 30kHz.
    <br><br><br>
    <strong>&#9313; Digital BNC Ports </strong><br>
    AIO features two pairs of digital input (DI-01, DI-02) and output (DO-01, DO-02) channels, each equipped with a BNC connector. The digital inputs support both 3.3V and 5V digital signals. The signal level for the BNC digital output ports can be configured via software to either 3.3V or 5V logic high. The digital I/Os operate at the same sample rate as the X-Headstage™ (XR, XSR mode). In NP mode, the sample rate is fixed at 30 kHz.
</div>

<br><br><br>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> Do not connect ports to unintended signal type. Permanet damage may occour.
</p>

<br><br><br>

![test1](<XDAQ AIO-16.png>)

<div class="text-block">
    <strong>&#9314; Thor Vision USB Port </strong><br>
    XDAQ AIO features a on-board hardware video processor capable of capturing up to four UVC camera streams simultaneously, or a single high-speed camera stream at up to 300 FPS. Each video frame is precisely time-stamped with the corresponding neural data acquisition timestamp.<br>
    By utilizing a dedicated hardware video encoding engine, the system ensures reliable, lossless frame capture—eliminating dropped or skipped frames commonly associated with software-based solutions.
    <br><br><br>
    <strong>&#9315; LED Driver Ports </strong><br>
    XDAQ AIO features 4ch of onboard high-power light source drivers. Drive LED light sources from commercial vendors like Thorlab, Plexon, TDT etc.<br>
    Stimulus intensity and modulation can be controlled independently of the main neural acquisition.Each light source driver supports up to 1A of power output and modulation frequency from DC to 10kHz.
    <br><br><br>
    <strong>&#9316; DB25 IO Port </strong><br>
    The DB25 connector provides six additional pairs of digital I/O channels. The digital inputs on the DB25 connector (DI-03 to DI-08) are compatible with both 3.3V and 5V digital signals. The digital outputs on the DB25 connector (DO-03 to DO-08) are designed for 3.3V logic high. The digital I/Os operate at the same sample rate as the X-Headstage™ (XR, XSR mode). The connector also includes supplementary device signals for interfacing with external devices.
    <br><br><br>
    <strong>&#9317; Ground Ports </strong><br>
    <strong>Sys GND — </strong> the digital ground shared by the internal electronic circuitry.<br>
    <strong>Chassis GND — </strong> connected to the metal enclosure, the outer shield of the HDMI cable, and earth ground via the power supply.<br>
    As a starting point, we recommend bonding the two ground ports together and using this common node to ground the Faraday cage shielding. Since environmental conditions can vary significantly, users should test and adjust the grounding configuration to determine the most effective setup for their specific environment.
    <br><br><br>
    <strong>&#9318; Expansion Ports </strong><br>
    The EXP1 and EXP2 ports connect to XDAQ™ accessories, such as the I/O Expander, to provide additional digital and analog I/O functionality.
    <br><br><br>
    <strong>&#9319; 3.5mm Audio Port </strong><br>
    This 3.5mm stereo jack enables audio monitoring of two selected headstage amplifier channels, configured via software: Analog Out 1 (AO-01), which is routed to the left audio channel, and Analog Out 2 (AO-02), which is routed to the right audio channel.
</div>

<br><br><br>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> Do not connect ports to unintended signal type. Permanet damage may occour.
</p>

<br><br><br><br><br><br>

### **Setting Up The Headstage And Probe**

<div class="text-block">
    <h4> For Record-Only (XR) or Stim-Record (XSR) Experiments </h4>
    1.&emsp;Connect the Type-D micro-HDMI connector of the stock KonteX HDMI cable to the X-Headstage™.<br>
    2.&emsp;Connect the Type-A HDMI connector to one of the XDAQ™ Headstage Ports. Always use Port 1, as other ports may be unavailable depending on the license purchased with the XDAQ™.<br>
    3.&emsp;Optionally, a commutator can be used between the headstage and the XDAQ™ Headstage Ports.<br>
    4.&emsp;Plug the electrode into the headstage.
</div>

<br>

<div class="text-block">
    <h4> For Neuropixels Experiments (NP Mode) </h4>
    1.&emsp;Connect the Omnetics connector of the Neuropixels cable to the headstage.<br>
    2.&emsp;Connect the USB-C connector of the cable to one of the Neuropixels Ports (Port 1–4).<br>
    3.&emsp;Optionally, a commutator can be used between the Neuropixels headstage and the XDAQ™. Refer to the Commutator User Manual for more information.<br>
    4.&emsp;Insert the Neuropixels probe into the headstage by connecting the flex cable of the Neuropixels probe to the headstage. Note: The metal pads on the flex cable should face downward when inserting it into the headstage. Flip the flex cable connector down to lock the probe in place.
</div>

<br><br><br><br><br><br>

### **Installing Driver & Software**

<div class="text-block">
   <h4>1. Connecting to a PC</h4>
    Use the supplied Thunderbolt cable to connect the Computer Port on the XDAQ™ to a Thunderbolt port on the PC. The cable is identifiable by the lightning bolt symbol on its connector.<br>
    The XDAQ™ can also supply power to the connected computer: CORE2 can deliver up to 15 W, sufficient to power most laptops. The Peripheral Port supplies up to 15 W of power.<br>
    The Peripheral Port can also be used to connect a Thunderbolt accessory, such as a storage device, which will be accessible from the host PC.
</div>

<br><br><br>

<div class="text-block">
   <h4>2. Download the driver</h4>
   <ul>
    <Li>Windows: https://developer.kontex.io </Li>
    <Li>macOS: Search for XDAQ™ from the App Store</Li>
    <Li>Linux: Contact us</Li>
    </ul>
</div>

<br><br><br>

<div class="text-block">
   <h4>3. Install the driver</h4>
   <strong>Windows</strong><br>
    1. Before installation, ensure that a "PCI Simple Communications Controller" is listed in the Device Manager.
</div>

![test1](<XDAQ AIO-17.png>)

<div class="text-block">
    2. Download and unzip the latest XDAQ™ driver from the KonteX website.<br>
    3. Locate "XDAQ.inf", right-click on it, and select “Install.”<br>
    4. Once the driver is successfully installed, this entry will update to "KonteX XDAQ".
</div>

![test１](<XDAQ AIO-18.png>)

br><br><br>

<div class="text-block">
   <h4>MacOS</h4>
   1.&emsp;Go to App Store, search for "XDAQ" and install "KONTEX XDAQ" app.
</div>

![test１](<XDAQ AIO-19.png>)

<div class="text-block">
   ２.&emsp;Open the XDAQ™ Application ("XDAQ Dext Loading Utils")
</div>

![test１](<XDAQ AIO-20.png>)

<div class="text-block">
   ３.&emsp;Click on "Load driver" button, A system message box will appear, click "Open System Settings". If you clicked OK instead, go to: System Settings / General / Login Items & Extensions
</div>

![test１](<XDAQ AIO-21.png>)

<div class="text-block">
   ４.&emsp;Enable XDAQ Dext Loading Utils
</div>

![test１](<XDAQ AIO-22.png>)

<div class="text-block">
   ５.&emsp;The App should display "Loading Status: Load successful"
</div>

![test１](<XDAQ AIO-23.png>)

<br><br><br>

<div class="text-block">
   <h4>4. Download the software</h4>
   XDAQ can run on popular open source applications.<br>
   Download the latest from our website: https:// www.kontex.io/software. Note that not all applications supports all experiment modes.
   <strong>XR Headstages (XR Mode):</strong><br>
    Open-Ephys ("Install XDAQ Plugin") or XDAQ-RHX
    <strong>XSR Headstages (XSR Mode):</strong><br>
    XDAQ-RHX
    <strong>Neuropixels (NP Mode):</strong><br>
    Open-Ephys ("Install XDAQ Neuropixels Plugin")
</div>

<br><br><br>

<div class="text-block">
   <h4>Verify Device Connection</h4>
   Once the PC is connected and the XDAQ™ is powered on, it should be automatically recognized by the operating system. For additional details, refer to the Install the Driver section.
</div>

<br><br><br>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> A USB-C data cable cannot substitute for the supplied Thunderbolt cable when connecting to the PC.
</p>

<p class="hanging-indent-NOTE">
  <strong>NOTE:</strong> The XDAQ™ is compatible with Thunderbolt cables up to 3 meters in length. If stock Thunderbolt cable will not be used, be sure to select an Intel/Apple-certified cable (identified by a lightning bolt symbol) that complies with Thunderbolt 3 or higher specification.
</p>

<br><br><br><br><br><br>

### **Updating The Firmware**

<div class="text-block">
    <p>KonteX may occationally release new firmwares for bug fixes and new functionalities. Additional capabilities may be enabled if they were not selected in the initial purchase (e.g. adding the SR128 capability or Neuropixels support).</p>
    <p>Check KonteX website (developer.kontex.io) for firmware update tool. Follow the prompt from the application to proceed.</p>
    When XDAQ™ is up to date.
</div>

![test１](<XDAQ AIO-24.png>)

<div class="text-block">
    <p>Upgrading XDAQ™</p>
</div>

![test１](<XDAQ AIO-25.png>)

<div clWhen XDAQ™ is not connected</p>
</div>

![test１](<XDAQ AIO-26.png>)

<br><br><br><br><br><br>

### **Starting The Application**

<div class="text-block">
    <h4>Check your firmware version before launching the application</h4>
    Before launching the application, please update the system firmware to the latest version.<br>
    Systems with the default “0-0-0” configuration will not be recognized properly by the software until the firmware update is completed.<br>
    Please refer to the Firmware Update section in this manual for detailed instructions before proceeding with any recording or stimulation experiments.
</div>

<div class="text-block">
    <h4>Run the record-only experiment (XR Mode)</h4>
    1.&emsp;Connect the XR headstage (X3R, X6R, or XeR) to the system using the KonteX HDMI cable.<br>
    2.&emsp;Launch a compatible application, such as Open-Ephys or XDAQ-RHX, downloaded from the KonteX website.<br>
    3.&emsp;If the XR Mode LED is not illuminated (indicating that the XR firmware is not loaded), the system will automatically boot into XR Mode when prompted by the software. This process may take a few minutes, after which the XR Mode LED should turn on.<br>
    4.&emsp;Once the application launches, it should detect the headstage and display the number of available channels.<br>
    5.&emsp;If the software does not detect the headstage, ensure that an XR-type headstage is correctly connected and securely attached. Restart the application or rescan the ports.<br>
</div>

<div class="text-block">
    <h4>Run the stimulation-recording experiment (XSR Mode)</h4>
    1.&emsp;Connect the XSR headstage (X3SR or XeSR) to the system using the KonteX HDMI cable.<br>
    2.&emsp;Launch a compatible application, such as Open-Ephys or XDAQ-RHX, downloaded from the KonteX website.<br>
    3.&emsp;If the XR Mode LED is not illuminated (indicating that the XR firmware is not loaded), the system will automatically boot into XR Mode when prompted by the software. This process may take a few minutes, after which the XR Mode LED should turn on.<br>
    4.&emsp;Once the application launches, it should detect the headstage and display the number of available channels.<br>
    5.&emsp;If the software does not detect the headstage, ensure that an XR-type headstage is correctly connected and securely attached. Restart the application or rescan the ports.<br>
</div>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> Using non-KonteX HDMI cables is possible but not recommended. Many commercial cables contain active electronics that can interfere with XDAQ™ communication and potentially damage the XDAQ™ system or the X-Headstage™.
</p>

<br><br><br>

<div class="text-block">
    <h4>Run the stimulation-recording experiment (XSR Mode)</h4>
    1.&emsp;Connect the Neuropixels probe and headstage to the XDAQ™.<br>
    2.&emsp;Copy the Neuropixels calibration data provided by IMEC into "OpenEphys/Calibrationinfo" folder.<br>
    3.&emsp;Launch the compatible application (OpenEphys XDAQ™ Neuropixels plugin, currently the only compatible open-source application) downloaded from the KonteX website.<br>
    4.&emsp;If the NP Mode LED is not illuminated (indicating that the Neuropixels firmware is not loaded), the system will automatically boot into NP Mode when prompted by the software. This process may take a few minutes, after which the NP Mode LED should turn on.<br>
    5.&emsp;Once the application starts, the software will automatically scan for installed probes and upload the corresponding calibration data. The XDAQ™ Neuropixels plugin GUI will display a green dot, indicating that the system is ready to begin streaming data.<br>
    6.&emsp;During data streaming, the Neuropixels Port LED will flash green and blue.<br>
    7.&emsp;If the PC experiences difficulty keeping up with the data transfer, the S2 LED will flash.
</div>

<br><br><br>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> Using non-KonteX HDMI cables is possible but not recommended. Many commercial cables contain active electronics that can interfere with XDAQ™ communication and potentially damage the XDAQ™ system or the X-Headstage™.
</p>

<br><br><br><br><br><br>

### **PC Requirement**

<div class="text-block">
    The XDAQTM AIO requires a modern PC with a minimum of a 6-core CPU, 16 GB of RAM, and at least one Thunderbolt 3 (or higher) port, identifiable by the lightning bolt symbol.
</div>

<br><br><br>

<div class="text-block">
    <h4>Reference PC configuration</h4>
    Apple Mac Mini M4 PRO 16GB<br>
    MSI Cubi Series with i7 or above
</div>

![test１](<XDAQ AIO-27.png>)

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> While Thunderbolt and USB-C share the same physical connector, they are not interchangeable. Thunderbolt offers significantly higher data transfer rates and requires specific compatible cables. Retrofitting a PC with a Thunderbolt add-on card is generally impractical, as these cards are model-specific and often incompatible with other systems. To prevent compatibility issues, users should verify that their PC includes native Thunderbolt support.
</p>

<br><br><br><br><br><br>

### **XDAQ™ DB25 IO Connector Pinout**

<div class="text-block">
    The DB25 connector on the XDAQ™ offers access to additional I/O ports and system signals. A breakout board is available to facilitate easy access to these signals via BNC connectors.
</div>

![test１](<XDAQ AIO-28.png>)

<br>

<div class="text-block">
    DAQ ON: Logic high at onset of a recording session<br>
    Sample CLK: is the sampling clock used to drive the X-Headstage™<br><br>
    All digital inputs (DI-01 to DI-08) are compatible with both 3.3V and 5V digital signals. The BNC digital output ports (DO-01, DO-02) can be configured via software to output either a 3.3V or 5V logic high signal. The digital output channels on the DB25 connector (DO-03 to DO-08) are designed for 3.3V logic high output.
</div>

<br><br><br><br><br><br>

### **Video Capture**

<div class="text-block">
    <h4>Comprehensive video capture of the test subject</h4>
    <ul>
    <Li>Simultaneous multi-camera(4ch) with guaranteed recording alignment with neural signal</Li>
    <Li>High frame rate(>100FPS) capture</Li>
    <Li>Synchronized DAQ time stamps and IO events directly encoded in the video meta data</Li>
    <Li>Supports wide variety of cameras from webcam to industrial</Li>
    </ul>
</div>

![test１](<XDAQ AIO-29.png>)

<div class="text-block">
    <h4>Software resources & downloads</h4>
    For camera setup instructions, recording configuration, and real-time viewing via Thor Vision, please visit our official software page (Thor Vision Software Portal: https://kontex-neuro.github.io/ThorVision/)
</div>

<br><br><br>

<p class="hanging-indent-IMP">
    &#9888; <strong>IMPORTANT:</strong> To ensure optimal performance distribution, users are advised to connect cameras or USB hubs evenly across the four USB ports on both sides of the system.
</p>

<br><br><br><br><br><br>

### **Accessory**

![test１](<XDAQ AIO-30.png>)

<br><br><br><br><br><br>

### **Technical Specifications - AIO**

![test１](<XDAQ AIO-31.png>)

<div class="text-block5">
    <p align="left">
    1. XR mode acquisition specifications are based on Intan Technologies’ RHD2000 series IC. In case of any discrepancies, the manufacturer's specifications shall take precedence.<br><br>
    2. The acquisition and stimulation specifications for XSR Mode are based on Intan Technologies' RHS2000 series IC. In case of any discrepancies, the manufacturer's specifications shall take precedence.<br><br>
    3. NP mode acquisition specifications are derived from IMEC’s Neuropixels 1.0 and 2.0 electrode. In case of any discrepancies, the manufacturer's specifications shall take precedence.</p>
</div>

<br><br><br><br><br><br>

### **Model Comparison**

![test１](<XDAQ AIO-32.png>)

<div class="text-block5">
    <p align="left">
    1. Neuropixel support (NP Mode) can be configured without the XR Mode or XSR Mode for passive probes.<br><br>
    2. Number of animals monitored can be increased using Port Expander, which provide each animal monitored with independent and isolated ground circuit.<br><br>
    3. Adpt-SR64 adapter is required to drive 64ch X3SR64 headstage.<br><br>
    4. IO Expander is required to increase the IO support.<br><br>
    5. Latency may vary with OS.</p>
</div>



<br><br><br><br><br>

---

![test2](LOGO-1.png)