# badusb-test

# Ultimate guide to HID attacks using Rubber Ducky scripts and Bad USB MITM attack

Have you ever wondered how hackers can compromise a computer with just a USB device? In this blogpost, we will explore the concept of HID attacks, which are a type of physical host attack that use a programmable device to emulate a keyboard or mouse and execute malicious commands on the target system. We will also learn how to use some of the tools that are part of the NetHunter system, such as HID Attacks, DuckHunter HID and Bad USB MITM Attack. We will also discuss the potential consequences of HID attacks, and how to protect against them. By understanding the risks and techniques involved in HID attacks, you can better secure your systems and protect against this type of attack vector.


## What is HID?

HIDs are devices that allow other devices such as a computer, smartphone, a television to receive input from them. These can be a keyboard, mouse, joystick, touchpad or Android with NetHunter.

This means that our Android once connected to a computer can recognized it as a keyboard. Not just a regular keyboard; rather keyboard that has already predefined what keys to type. It can be programmed to inject keystrokes into a computer as if they were being typed on a keyboard, allowing it to execute a pre-defined set of actions on the host device.

Besides Android, there are several devices that are used to carry out an HID attack. These are known as Rubber Ducky or BadUSB. Here are few examples:


<details open>
    <summary>Rubber Ducky:</summary>
    <ul>
        <li>A Rubber Ducky is a small, programmable USB device that resembles a USB flash drive. It can be programmed to inject keystrokes into a computer as if they were being typed on a keyboard, allowing it to execute a pre-determined set of actions on the host device.</li>
    </ul>
 </details>
 
![usb-rubber-ducky-badusb-nowa-wersja-v2-534758_1200x1200](https://github.com/MMVonnSeek/badusb-test/assets/89359847/c0769d0a-8897-4578-a458-995272d3ce48)

<details open>
    <summary>Teensy:</summary>
    <ul>
        <li>A Teensy is a small, programmable microcontroller that can be programmed to behave as an HID device. It can be used to inject keystrokes or other input into a host device.</li>
    </ul>
 </details>

![driveby](https://github.com/MMVonnSeek/badusb-test/assets/89359847/97aa802e-107d-4d3b-bfaa-0a619827c26b)


 <details open>
    <summary>Bash Bunny</summary>
    <ul>
        <li>A Bash Bunny is a small, programmable USB device that can be used to carry out a variety of attacks, including HID attacks. It can be programmed to inject keystrokes or other input into a host device, or to execute scripts and commands on the device.</li>
    </ul>
 </details>

![bash-bunny-mk2_001_c58d9658-b151-4328-af26-11eef3c47355_2000x](https://github.com/MMVonnSeek/badusb-test/assets/89359847/acdc7bd9-8d3d-4517-b048-a43cd7490d77)


 <details open>
    <summary>Raspberry Pi:</summary>
    <ul>
        <li> A Raspberry Pi is a small, single-board computer that can be used to carry out a variety of attacks, including HID attacks. It can be programmed to behave as a HID device and to inject keystrokes or other input into a host device.</li>
    </ul>
 </details>

![download](https://github.com/MMVonnSeek/badusb-test/assets/89359847/0354432f-053f-468c-9461-d95cf7cfb2e3)


 <details open>
    <summary>Digispark Attiny85 Arduino:</summary>
    <ul>
        <li>An Arduino is a small and cheap, programmable microcontroller that can be used to carry out a variety of attacks, including HID attacks. It can be programmed to behave as an HID device and to inject keystrokes or other input into a host device.</li>
    </ul>
 </details>

![m_dulo_digispark_-_attiny85_-_usb_-_](https://github.com/MMVonnSeek/badusb-test/assets/89359847/662cbbbf-6589-451b-ab78-a6427bee3944)


 <details open>
    <summary>WiFi HID Injector (WHID):</summary>
    <ul>
        <li>WHID attacks are a type of wireless HID attack, which means that they do not require a physical connection to the target device. Instead, the attacker could remotely inject keystrokes or other input into the device over a Wi-Fi connection. This can make WHID attacks particularly difficult to detect, as the injected input may not be visible to the user.</li>
    </ul>
 </details>

![collage](https://github.com/MMVonnSeek/badusb-test/assets/89359847/4f0cc29d-40e9-472e-8baf-0e26aa9b697d)


 <details open>
    <summary>OMG cable:</summary>
    <ul>
        <li>It is also known as the O.MG Cable. It is a USB cable that looks like an ordinary charging cable but is designed with hidden malicious capabilities. Created by security researcher Mike Grover, aka MG, the OMG Cable is equipped with a Wi-Fi-enabled module, allowing attackers to remotely access and control a connected device. When a user connects the OMG Cable to their device, the hidden implant automatically establishes a wireless connection to the attacker’s device or network.</li>
    </ul>
 </details>

![50068-98202-OMG-Elite-xl](https://github.com/MMVonnSeek/badusb-test/assets/89359847/0cd71395-47fd-4d1f-b375-4fab9b2ac881)


 <details open>
    <summary>Smartwatch:</summary>
    <ul>
        <li>TicWatch Pro smartwatches with installed NetHunter can also behave as Rubber Ducky devices and execute custom scripts on targeted system.</li>
    </ul>
 </details>



  <details open>
    <summary>Flipper Zero:</summary>
    <ul>
        <li>Flipper Zero is a portable multi-tool device that can interact with various wireless protocols and interfaces, such as infrared, radio frequency, NFC, iButton, and more. In our scenario, it can also act as a BadUSB device by emulating a keyboard or a mouse and run Rubber Ducky scripts.</li>
    </ul>
 </details>



 <details open>
    <summary>Smartphone:</summary>
    <ul>
        <li>Rooted Android device can behave as HID to execute Rubber Ducky scripts. It is possible to run these scripts with and without NetHuner.</li>
    </ul>
 </details>
