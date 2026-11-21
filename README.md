# Paltalk Dark Mode Created By SodaDaPimp

Copyright (c) 2026 SodaDaPimp. All rights reserved.

## SCREENSHOTS

**Red theme**

![Paltalk Dark Mode - Red theme](Screenshot%202026-11-20%20230427.png)

**Green theme**

![Paltalk Dark Mode - Green theme](Screenshot%202026-11-20%20230513.png)

**Pink theme**

![Paltalk Dark Mode - Pink theme](Screenshot%202026-11-20%20230535.png)

**Purple theme**

![Paltalk Dark Mode - Purple theme](Screenshot%202026-11-20%20230611.png)

## WHAT IT DOES

Paltalk draws its own windows, so Windows' dark mode cannot change them.
This program darkens Paltalk from the INSIDE: a small theme engine (built
into the program) is loaded into the running Paltalk and recolours everything
Paltalk paints - every chat room, the chat text, user lists, the Pal list /
messenger, menus, dialogs and the window title bars. Backgrounds become dark,
text becomes light, the blue headers become deep dark.

**COLOUR THEMES:** besides Dark you can pick Red, Green, Blue, Pink, Purple,
Orange, Yellow, Silver, Grey or Brown. The whole of Paltalk (backgrounds,
headers, buttons, links, popped-out webcam windows and the window title
bars) takes on that colour, still dark and easy on the eyes. Click a colour
in the program window, or use the tray icon's "Colour theme" menu. It
changes live and is remembered.

Webcams, video and photos are real pictures (not colours), so they are never
touched and always look natural.

Because Paltalk itself is dark, nothing is drawn on top of your screen:
there is nothing that can leak white, windows in front of Paltalk are never
affected, and screenshots and screen recordings (any method, also "window
capture") show Paltalk dark.

## HOW TO USE

1. Double-click `Paltalk Dark Mode Created By SodaDaPimp.exe`.
   It is one single file; nothing has to be installed and nothing else has
   to be next to it.
2. Click the big ON / OFF switch. Paltalk switches live, you do not have to
   restart it. Pick a colour under "Colour theme" (Dark is the normal dark
   look). Choosing a colour while the switch is OFF turns it ON.
3. Closing the window keeps it running in the tray (moon icon).
   Right-click the moon icon for Open / Dark mode / Colour theme / Exit.
4. Ctrl+Alt+D turns dark mode on or off from anywhere.
5. "Start with Windows" starts it hidden in the tray at sign-in. It then
   darkens Paltalk by itself every time Paltalk starts.

To stop it completely use Quit (in the window) or Exit (tray menu). Paltalk
goes back to its normal colours within a second.

## REQUIREMENTS

Windows 10 / 11 (64 bit) and the current Paltalk (the Qt based version).
Nothing else needs to be installed.

## GOOD TO KNOW

- Nothing of Paltalk is changed on disk: Paltalk's files are never touched.
  The engine lives only in the memory of the running Paltalk. Turning OFF,
  quitting or stopping the program (even if it is killed) brings back the
  normal look.
- Your settings, the log and the engine file are kept in
  `%LOCALAPPDATA%\PaltalkDarkMode` (paste that into the Explorer address bar).
  Delete that folder to reset everything. If a `PaltalkDarkMode.ini` already
  sits next to the .exe, that folder is used instead (portable use).
- Best result: start the program before Paltalk (or turn on "Start with
  Windows"), or restart Paltalk once after you first turn dark mode on. If
  Paltalk was already running, a few list entries that Paltalk painted a
  moment earlier can stay dim (or keep the old colour after a colour change)
  until Paltalk redraws them - scrolling or reopening the room does it.
- Small pictures such as the blue rank shields next to names are images, not
  colours, so they keep their own colours.
- Paltalk's built-in web pages (the "Home" dashboard, ads, some shop pages)
  are a separate browser engine inside Paltalk. They are not recoloured by
  this program (some of them are dark by themselves).
- If a Paltalk update ever changes Paltalk's Qt version so much that the
  engine does not fit any more, the program notices and falls back to a
  simpler "screen overlay" method automatically (a dark filter drawn exactly
  over the Paltalk windows, always Dark). Dark mode still works, but
  screenshots and recordings that capture only the Paltalk window then show
  the old colours.
- The program is not code-signed and it loads the engine into Paltalk the way
  many Windows tools do (a standard Windows hook). SmartScreen or an
  antivirus program may ask once or even warn - choose "More info" /
  "Run anyway" or allow the program.
- `PaltalkDarkMode.log` is the log of the program, `PaltalkDarkMode.hook.log` is
  the log of the engine inside Paltalk. If something looks wrong, the first
  lines say what happened.
- If the program ever crashes it writes a note to the log and starts itself
  again.
- This program is an independent work. It is not made by, and has nothing to
  do with, Paltalk.
