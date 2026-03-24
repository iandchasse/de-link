# Philosophy

## Why This Exists

This project started because I wanted to read books. And after my kindle's frontlight broke, I thought of making an ESP32-based e-reader device that worked the way I wanted it to with all aspects of the product in my control. This is simply just my first post-grad "side project". I thought an e-reader didn't have to have the processing power and RAM that a Linux-based device typically has. So I breadboarded something simple, hit many walls in software trying to work on the shoulders of [GxEPD2](https://github.com/ZinggJM/GxEPD2) and [diy-esp32-epub-reader](https://github.com/atomic14/diy-esp32-epub-reader), switched to building the PCB (my first one ever), the "XTEink X4" came out, realized it was mostly everything I wanted, almost gave up, went onward with the hardware design when I saw some of the flaws of that device, realized there might still be a market for people who might want a device like this to be open-source.

So I ended up building the rest of the prototype PCB, making an enclosure, and forking over software from [crosspoint-reader](https://github.com/crosspoint-reader/crosspoint-reader) for an e-reader experience instantly comparable to what XTEink owners have. I now use my prototype to read, which was my initial goal.

## Not Competing

There are already great devices in this space. The M5Paper S3 is a polished development kit with a beautiful screen. The XTEink X4 and X3 are ultra-portable readers that are the sole reason why my prototype has working firmware. These are real products made by real companies with manufacturing pipelines and supply chains and customer support teams. This project is none of those things, and it doesn't try to be.

Please see COMPARISON.md for a full "comparison" between de-link and those devices.

As the market continues to expand off of the initial idea for an ESP32-based e-reader, I want to ensure that there is an alternative that is easily revisable by the community in order to uphold the functional standards of these pre-built devices. A device you have full control over will always have better support and longevity, and a device using cheap electronics like these off-the-shelf e-paper displays should not rely on overseas RMA processes and/or "it's cheap, might as well buy another", promoting e-waste of a perfectly accessible and recyclable platform in the ESP32.

## The Case for Building It Yourself

E-paper is really cool, and reading on it is an experience like no other. Like mentioned before, the technology can be rather cheap and non-durable. A GoodDisplay panel runs about $10-25. An ESP32-S3 module is a few dollars. A LiPo cell, a USB-C connector, some passives, the full BOM costs less than what most people spend on a phone case. And when a $20 screen cracks or a $5 MCU dies, you desolder it and put a new one on. You don't file a support ticket, you don't wait for a shipping label, and you don't throw the whole thing away.

That's the real argument for building it yourself. Not that it's cheaper up front (though it can be), and not that it's necessarily better than what you can buy (the XTEink devices are genuinely impressive for what they are, and also, most used e-readers on FaceBook Marketplace go for cheaper and are much more functional and durable than these ESP32 based ones). The argument is that you end up with something you can actually understand and contribute to if you wanted to. If a problem comes up, you can reference the community for why that problem exists and how to fix it, and rely less on the company that sold you it.

All of the development on this project is essentially my first:

- my first schematic/PCB
- my first GitHub repos I intend to share and maintain
- my first functional part design
- my first functional 3D print

Because of this, I feel especially confident that others with the same or more experience could expand and contribute on this project further than I ever could think.

## Open by Default

I'll be straightforward: I didn't open-source this project just because I'm passionate about open hardware. It's also because I'm just one person with a prototype on my desk and in the middle of paying off student loan debt. I'm in a fortunate position to be in a comfortable living situation working full-time while I develop this project, but I do not have the resources at this moment to pursue actual product development. More details are in ROADMAP.md.

## In Short

I built an e-reader because my Kindle broke and I'm stubborn. It works. I use it every day. Here's how to build your own.
