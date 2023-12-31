# OpenVR-VisibleFloorBoundaries
Ensures the floor borders of your playspace always stays nice and visible.

SteamVR likes to dim your boundaries while you are physically near the boundaries. In certain cases, such as when you *need* floor boundaries always on, this can make your boundaries very difficult to see. This OpenVR program will draw its own floor boundary (only as a rectangle atm), with the specified colors, transparency, and thickness.

## To-Do
- Figure out how I wanna release this application. Releasing this application in a safe manner/less scary than running an .exe file from online.
- ~~Better handling of running the program while OpenVR hasn't fully initialized yet.~~
- ~~Make changing the size of the playspace dynamic if a change is detected.~~
- Add config file to adjust colors and other settings.
- Add the option to use colors and transparency from what is set in SteamVR.
- Perhaps properly register this as a SteamVR app.
- Additional/optional boundary border color option for more contrast in the case where the original boundary color blends in too much to the surrounding environment.

## Credits
#[cntools/rawdraw](https://github.com/cntools/rawdraw)
A wonderful C library of simple drawing tools.

#[CNLohr - One hour. Two ways. C in Windows. OpenVR overlays from scratch.](https://www.youtube.com/watch?v=r6kM3tR03g4)
Fantastic video introduction into using the OpenVR API in C along with CNTool's RawDraw.

## Media
You can see how my own created boundary is much more bright than the suddenly dim chaperone bounds!
![OpenVRPlayspace](https://github.com/SableVII/OpenVR-VisibleFloorBoundaries/assets/143745362/4ffd80ec-3c24-4815-839c-a7a9ba7b4bd8)

