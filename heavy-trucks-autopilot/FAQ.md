# FAQ

**Do I have to install it myself?**
No. It's a dependency of Heavy Trucks (Vanilla+) and installs automatically.

**How do I make a truck drive itself?**
Research **Heavy logistics** and build **truck stops**. Open a truck, add stops to its **schedule** (the "Schedule" tab, like a locomotive's) with their wait conditions, and switch it to **Automatic**.

**Does it work like trains?**
Mostly, yes: wait conditions, temporary stops, interrupts, truck groups, and truck limit and priority on the stops. Stops in a row work as one lane.

**Can I make trucks pass through a point without stopping there?**
Add a truck stop to the schedule with **no wait conditions**: the truck drives to it and goes straight on to the next one, like a train waypoint.

**Do trucks use my roads?**
Yes (since 1.0.0), found by themselves, nothing to mark. A road is the space between **two yellow lines of hazard concrete**, a **strip of hazard concrete**, or a **street of paving** (concrete, stone path...) with something else either side: 5 to 12 tiles wide, straight, at least 16 tiles long. Roads from **Transport Drones** and tiles other mods mark as roads count too. Diagonal roads aren't supported yet.
Turn it off for the whole map in the mod settings (**Trucks use roads**) or for one truck with **Use roads** in its truck tab.

**My truck drives across country instead of using the road.**
It takes the road when one leads where it's going and isn't much longer than driving straight there (at most twice as long by default: **Longest detour along roads** in the mod settings). Also check that the road is at least 5 tiles wide and straight.

**Why are the headlights on / off?**
The game only turns a vehicle's lights on with someone driving it, so the Autopilot turns them on itself while a truck is in automatic mode.

**Can I filter or limit the cargo slots?**
Yes, in the truck window: **middle-click** a slot to filter it, and the **red button** next to "Trunk" limits the trunk like a chest.

**Does it cost performance?**
Only for trucks that are driving. There are no periodic searches of the map, so a big map with no trucks costs nothing.

**Will it work with Factorio 2.1?**
Yes, it will be updated when 2.1 is out as stable.

**A truck got stuck / did something odd.**
Please post it in the **Discussion** tab, with a screenshot or a save if you can. It helps a lot!
