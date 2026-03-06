[img]https://i.imgur.com/f6Ih8zb.gif[/img]
[img]https://i.imgur.com/TnrVYPe.png[/img]
[img]https://i.imgur.com/3kAQyVe.gif[/img]

[img]https://i.imgur.com/TkXwqUi.png[/img]
[h1]Logistical Capacity for Navies[/h1]
[b]Logistical Capacity for Navies[/b] is a total overhaul of how naval force limits work. Instead of using arbitrary hard caps or basic ship counts, this mod introduces a dynamic system that scales your capacity based on your actual industrial power and dockyard efficiency.

[img]https://i.imgur.com/vswcW0W.png[/img]
[h2]Logistics over Limitation[/h2]
Vanilla HOI4 doesn't account for the massive logistical strain of a global fleet. This isn't a "hard limiter" that stops production; it’s an industrial simulation. If you want a massive navy, you need the industrial mobilization to back it up.

[list]
[*] [b]Ship Weighting:[/b] We don't just count hulls. When enabled, larger ships like Battleships or Carriers contribute more to your total load than simple screens.
[*] [b]Industrial Scaling:[/b] Your capacity is driven by a weighted formula: [b](Dockyards * 10) + (Mils * 0.5) + (Civs * 0.5)[/b].
[*] [b]Economic Mobilization Impact:[/b] Your logistical efficiency is tied to your Consumer Goods. A Civilian Economy will struggle to support a massive fleet, while a War Economy provides full logistical reach.
[*] [b]Interactive UI:[/b] Includes a live GUI in the deployment and country views. [b]Click the indicator[/b] to refresh your logistics status immediately!
[*] [b]Multilingual Support:[/b] Now localized for Russian and Simplified-Chinese via LLM-assisted translations.
[/list]

[h2]Scaling Calculation Options[/h2]
Customize how your navy scales using Game Rules. Each choice changes how penalties and bonuses are calculated:
[list]
[*] [b]Absolute Distance:[/b] Logistics are based on the raw number of ships over or under the cap. A gap of 10 ships provides the same bonus regardless of country size.
[*] [b]Saturation Percentage:[/b] Logistics are based on the percentage of capacity used. This allows smaller nations with a 0/10 fleet to receive the same maximum efficiency bonus as a superpower with a 0/200 fleet.
[/list]

[h2]Unique Logistics Formulas[/h2]
Choose the mathematical curve that best fits your playstyle:
[list]
[*] [b]Linear (Consistent):[/b] Efficiency changes at a flat, constant rate. Every ship over your capacity adds the exact same penalty.
[*] [b]Quadratic (Scaling):[/b] Penalties start small but accelerate rapidly as you exceed your capacity.
[*] [b]Sigmoid (Balanced):[/b] Features a "soft" start for minor over-extensions, but scales sharply in the middle.
[*] [b]Logarithmic (Early Impact):[/b] Early ships over the cap have a high impact on efficiency, but the penalty growth slows down significantly as your fleet continues to grow.
[*] [b]Step Function (Milestones):[/b] Efficiency drops in sudden, large "steps" at specific milestones (e.g., crossing -1, -50, or -100 over cap).
[*] [b]Hyperbolic (Critical):[/b] The "Death Spiral." Penalties are manageable until you approach a critical buffer, at which point logistics collapse entirely.
[/list]

[h2]Key Features[/h2]
[list]
[*] [b]Infrastructure Upkeep:[/b] Large industrial bases now face diminishing returns. Your total dockyard count creates a "Strain Factor" that dilutes your production bonuses, rewarding efficient "Tall" play over mindless dockyard spam.
[*] [b]Ship Weighting Toggle:[/b] Choose between "Uniform" (1 Ship = 1 Cap) or "Weighted" (Hull-based) load calculations.
[*] [b]Logistics Safety Clamp:[/b] Optional game rule to prevent naval production penalties from exceeding -100%, ensuring your shipyards never truly "die."
[*] [b]No Buffs (Over-Capacity Focus):[/b] Removes all under-capacity bonuses and uncaps penalties. Includes a dockyard-based convoy trickle to prevent total economic death.
[*] [b]Dynamic Tooltips:[/b] Hover over the indicator to see a full [b]Fleet Breakdown[/b], including the individual weight values of your Battleships, Carriers, and even modded units.
[/list]

[h2]Technical Info[/h2]
[list]
[*] [b]Base Capacity:[/b] (Dockyards * 10) + (Mils * 0.5) + (Civ * 0.5)
[*] [b]Weighted Values:[/b] Subs/DD (1.0), Cruisers (2.0), Battleships/Battlecruisers (4.0), Carriers (5.0)
[*] [b]Refresh Rate:[/b] Monthly pulse, On Startup, or Manual Click
[/list]

[i]Modder’s Note: This system makes dockyards and total industry matter more than ever. Check the in-game tooltip for a full breakdown of your current industrial weights and mobilization efficiency![/i]

[h1]Information[/h1]
We are centralizing our mod support to ensure bugs and suggestions are handled quickly. We rarely respond to Steam comments, so please join our communities below:
[img]https://i.imgur.com/yTWuTOb.png[/img]
[b]Better Mechanics Support:[/b]
For general collection feedback and technical support, join the [url=https://discord.gg/y2pRQWggTn]Better Mechanics Discord Server[/url].

[b]Choo_Choo_Oreo's Collection:[/b]
For specific requests regarding this mod and my other projects, join my [url=https://discord.gg/6qDDTEVyC3]Personal Discord Server[/url].

[h2]Support the Developer[/h2]
If you enjoy the work and want to support future development:
[url=ko-fi.com/choo_choo_oreo] ☕ Commission Me on Ko-Fi[/url], Commission me to update or port HOI4 mods.
[url=patreon.com/Choo_Choo_Oreo] 🎖️ Support Me on Patreon[/url], I post updates for my main mod here.

[h1]Check out my other mods![/h1]
[url=steamcommunity.com/sharedfiles/filedetails/?id=1553726074] Continents are Countries[/url], Balanced continental nations competing in a free-for-all.
[url=steamcommunity.com/sharedfiles/filedetails/?id=3301072102] A New Chapter - Fantasy Overhaul[/url], My passion project, a full fantasy overhaul of HOI4.
[url=steamcommunity.com/sharedfiles/filedetails/?id=3644205838] FAI - Fantasy AI[/url], An AI mod compatible with most fantasy overhaul and alt-history mods.
[url=steamcommunity.com/sharedfiles/filedetails/?id=1556140404] We Shall Never Surrender: Desperate Defence[/url], Adds surrender offset decisions and defence modifiers when your nation is losing.
[url=steamcommunity.com/sharedfiles/filedetails/?id=1894899147] Declare War on Everyone Button[/url], A single button to declare war on the entire world.
[url=steamcommunity.com/sharedfiles/filedetails/?id=2877503144] Set Your Country Rules![/url], Customize the rules governing your country in-game.