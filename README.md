<!DOCTYPE html>
<html lang="en">
<head>

</head>
<body>
    <h1>Motherboard & BIOS Guide</h1>

    <section>
        <h2>What Is a Motherboard?</h2>
        <p>A motherboard is a printed circuit board (PCB) that contains ports, sockets, control chips, and connection pathways. Its main function is to bring all computer components together into one organized system. Without the motherboard, the processor, memory, storage, and graphics card cannot work together.</p>

        <h3>Main Components of a Motherboard</h3>
        <ol>
            <li><strong>CPU Socket:</strong> This is where the processor is installed. Socket types vary between companies like Intel and AMD, and each processor generation has its own socket that supports its specifications.</li>
            <li><strong>Chipset:</strong> Considered the “second brain” of the motherboard, it manages data flow between the processor and other components. The chipset determines motherboard features such as overclocking support, memory type, and the number of ports.</li>
            <li><strong>RAM Slots:</strong> Used to install random-access memory. They typically range from 2 to 8 slots and support technologies like DDR4 or DDR5.</li>
            <li><strong>PCIe Slots:</strong> Used to install graphics cards, network cards, sound cards, and storage expansion cards. The most common slot is PCIe x16, usually dedicated to the graphics card.</li>
            <li><strong>Storage Ports:</strong> These include SATA for traditional HDD and SSD drives, and M.2 NVMe for ultra-fast storage.</li>
            <li><strong>Power Connectors (ATX 24-Pin + CPU 8-Pin):</strong> Deliver power from the power supply to the motherboard and CPU.</li>
            <li><strong>BIOS / UEFI:</strong> A small operating firmware that boots the system and initializes hardware before the main operating system starts.</li>
            <li><strong>CMOS Battery:</strong> Stores BIOS settings and system time even after power is disconnected.</li>
        </ol>

        <h3>Main Functions of the Motherboard</h3>
        <ul>
            <li>Connecting all hardware components and coordinating their operation</li>
            <li>Routing data between the CPU, memory, and storage</li>
            <li>Providing ports for external devices</li>
            <li>Offering protection circuits and power regulation</li>
            <li>Booting the system via BIOS/UEFI</li>
        </ul>

        <h3>Types of Motherboards</h3>
        <ol>
            <li><strong>ATX:</strong> The most common type; offers many features and more expansion ports.</li>
            <li><strong>Micro-ATX:</strong> Slightly smaller and suitable for mid-range desktop systems.</li>
            <li><strong>Mini-ITX:</strong> Very small; ideal for compact and quiet computers.</li>
        </ol>

        <h3>Factors to Consider When Choosing a Motherboard</h3>
        <ul>
            <li>CPU socket compatibility</li>
            <li>Supported RAM type and speeds</li>
            <li>Number of PCIe slots</li>
            <li>Number of M.2 and SATA ports</li>
            <li>Build quality and cooling features</li>
            <li>Overclocking support if needed</li>
            <li>Budget</li>
        </ul>
    </section>

    <section>
        <h2>What Is BIOS?</h2>
        <p>The BIOS (Basic Input/Output System) is a program stored in a non-volatile memory chip on the motherboard. Its main tasks include initializing components, running POST, loading the OS, and providing a setup interface.</p>

        <h3>Main Functions of BIOS</h3>
        <ol>
            <li><strong>POST (Power-On Self-Test):</strong> Checks essential hardware components at startup. Produces beeps or messages if errors occur.</li>
            <li><strong>Boot Loader:</strong> Determines which device to load the operating system from. Boot order can be changed in BIOS settings.</li>
            <li><strong>Setup Utility (Hardware Settings):</strong> Control CPU speed, RAM frequency, graphics card settings, and fan/power management.</li>
            <li><strong>BIOS API:</strong> Older systems rely on BIOS to provide basic disk and text functions before the OS starts.</li>
        </ol>

        <h3>Types of BIOS</h3>
        <ol>
            <li><strong>Legacy BIOS:</strong> Exists since the 1980s. Limited to 2.2 TB bootable storage, text interface, no fast boot, no Secure Boot.</li>
            <li><strong>UEFI (Unified Extensible Firmware Interface):</strong> Advanced version of BIOS. Supports disks >2.2 TB, graphical interface, Secure Boot, faster boot, networking, and running apps directly from firmware.</li>
        </ol>

        <h3>BIOS vs UEFI Comparison</h3>
        <table>
            <tr>
                <th>Feature</th>
                <th>Legacy BIOS</th>
                <th>UEFI</th>
            </tr>
            <tr>
                <td>User Interface</td>
                <td>Text-based</td>
                <td>Graphical + Mouse</td>
            </tr>
            <tr>
                <td>Supported Boot Size</td>
                <td>Up to 2.2 TB</td>
                <td>More than 9 ZB</td>
            </tr>
            <tr>
                <td>Security</td>
                <td>Limited</td>
                <td>Secure Boot</td>
            </tr>
            <tr>
                <td>Speed</td>
                <td>Relatively slow</td>
                <td>Very fast</td>
            </tr>
            <tr>
                <td>Network Support</td>
                <td>No</td>
                <td>Yes</td>
            </tr>
            <tr>
                <td>Expansion & Customization</td>
                <td>Limited</td>
                <td>High</td>
            </tr>
        </table>

        <h3>Importance of BIOS</h3>
        <ul>
            <li>Ensures the computer works correctly at startup.</li>
            <li>Controls boot order and input/output devices.</li>
            <li>Protects the system from malware before the OS loads.</li>
            <li>Enhances performance via CPU, memory, and graphics card settings.</li>
        </ul>

        <h3>Important Tips When Using BIOS</h3>
        <ul>
            <li>Avoid random changes: Incorrect modifications may prevent the system from booting.</li>
            <li>Keep factory settings: Can be restored if problems occur.</li>
            <li>Update BIOS carefully: Can improve performance and support new CPUs, but carries risks if done incorrectly.</li>
            <li>Use UEFI when possible: For faster boot and modern security benefits.</li>
        </ul>
    </section>
</body>
</html>

