# GMA-950-backport-for-915
Backport GMA 950 drivers to the 915GM!


IMPORTANT!

This is simply a backport of the 15.22.58.2993 Windows Vista / 7 drivers from the GMA 950 to the 915GM.

This does NOT enable Aero, as the 915GM simply lacks the required features in hardware!



The goal:

The goal of this project is to bring better support for the 915GM under Vista and Windows 7. While certain features like Aero are off-limits, it is theoretically possible to enable features such as OpenGL 1.5 (rather than 1.4) on the 915GM, as it DOES have the hardware for it, drivers are just the missing piece.

Essentially: Stability and OpenGL 1.5 support, as well as partial WDDM compatability!


Keep in mind that while this may work, it is not guarenteed to be 100% stable!


Feel free to check the INF file, it's mostly just code from newer drivers anyways.



Why?


The 915GM and GMA 950 were released roughly around the same time (~2005).

However, while the GMA 950 went on to receive support up until 2013, the 915GM was completely abandoned in 2007, it never even got updated past XPDM drivers!



32 BIT ONLY!!!!

