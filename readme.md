Hi, just an FYI - I was not able to get Animal Crossing GC Multiplayer running.

It uses a batch file that calls a powershell file that calls an exe that calls another exe.

The main complications with managing this through AMP:

  1. The powershell script writes a second, actual, config file using settings specified in the server settings file. This is hard to replicate with AMP.
  2. I have no clue how the first exe is calling the other exe and I don't have the patience to find out.
  3. Apparently a second window is supposed to pop up with settings for the town name and stuff that needs user input. I don't know if that's doable with AMP.

Basically, this app needs a simpler configuration process. If it was just a launcher and subprocess that'd be doable, but there's too much going on for me to want to spend time getting things sorted.
