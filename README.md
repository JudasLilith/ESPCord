## ESPCord

* An ESP32-based  PCB to connect to Wall adapters for controlling power to SBCs.

### Why make this?

* I normally use a small Raspberry Pi Zero in order for me to control my Octoprint setup, but due to the board being connected constantly it cannot shut down with the normal octoprint UI. This is when I thought that I should have a method of controlling the power going to the Setup, so that it can properly reboot every time I manipulate its power source by being connected to Home Assistant.

* ### Don't you have wall plugs that do this?

  * You're absolutely right! however:
    * The prices are at least 30 dollars a pop
    * most of the cheaper ones want you to use their own crummy software
    * It's closed source(yuck!)
    * most of them connect to wall sockets, so if you move between countries where one uses 110 and the other uses 220, it's better to just connect from the wall adapter itself(since you know that the voltage coming from there is a regulated 5v.)

* [ ] Build Zine page
* [ ] find the one piece
* [ ] Finish PCB
* [ ] Make a schematic
* [ ] Program so it actually works(Easiest one here)
* [ ]
