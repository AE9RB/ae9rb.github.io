---
layout: leap-day
title: David Turnbull
description: "Amateur Radio: AE9RB"
tagline: I make things.
---
<style>
.right { float: right; clear: right; margin-left: 7px}
h1 { clear: right; width: 100%;}
#banner .tagline { padding: 10px; font-size: 16px; max-width: 600px;  margin: 6px auto; }
</style>

# [64K BASIC](https://www.basic-lang.org/)
![Screenshot](../assets/basic1701.png){: .right}

The lingua franca of 70s and 80s personal computers. BASIC programs were widely distributed in books and magazines for users to type in. I wanted to get good at Rust so I wrote this as a compiler and process virtual machine. What started as a learning exercise turned into a preservation project.

# [Peaberry SDR](peaberry)
![Screenshot](../assets/peaberry/peaberryCW.jpg){: .right}
![Screenshot](../assets/peaberry/peaberryV2.jpg){: .right}

This radio uses [skywave](https://en.wikipedia.org/wiki/Skywave)
propogation to make 7000 km contacts across the Pacific Ocean with
only one watt of transmitted power. Imagine an LED or a candle
blinking on your roof in the United States and someone in
Australia decoding the message.

It uses a quadrature mixer to sample I/Q with a Delta-Sigma ADC/DAC
and connects as a USB device. The radio has its own
[PC and Mac software](https://github.com/AE9RB/peaberry-cw)
written in C++. The Cypress PSoC was programmed in
[C and Verilog](https://github.com/AE9RB/peaberry).

I sold this as a kit for a few years. Reviews are in the
[November 2013 issue of QST](http://www.arrl.org/files/file/QST/This%20Month%20in%20QST/November%202013/TOC.pdf) pg 57-59
and on [eHam](https://www.eham.net/reviews/view-product?id=10690)
[(alt)](https://www.eham.net/reviews/view-product?id=11577).
The forums can be read at the
[Internet Archive](https://web.archive.org/web/20200204160704/http://ae9rb.com:80/forum/).

# [SwiftGL](https://swiftgl.github.io/)
![Screenshot](assets/swiftgl.png){: .right}

Swift was new and lacking native libraries, so I created
an OpenGL interface, math library, and image decoding library.
Despite type annotating everything possible, the inference system
hit a performance wall when I was about 80% done. It's 100% done now.
Apple later deprecated OpenGL from all its products.

# [Iambic Keyer](https://github.com/AE9RB/iambino)
![Screenshot](../assets/iambino1.jpg){: .right}

This is a device radio operators use to send morse code. I forced myself to build it with thru-hole parts as an Arduino shield, which made the hardware expensive and software complicated. But it works perfectly with shaped sine waves and zero-lag.

# [Frobnitz](http://frobnitz.sourceforge.net/)
![Screenshot](assets/frobnitz.png){: .right}

The text adventures from Infocom ran on a VM called the
[Z-machine](https://en.wikipedia.org/wiki/Z-machine).
Making it run on Palm simply required the entire VM to be implemented as a state machine.

# [Mr. Label Maker](assets/labelmaker.d64.zip)
![Screenshot](assets/labelmaker.jpg){: .right}

For the [Commodore 64](https://en.wikipedia.org/wiki/Commodore_64).
Create labels for your 5.25" floppy diskettes using the built-in
graphics editor. The source and manual are lost to time, but this
is a cracked copy that survived because of the warez scene.
