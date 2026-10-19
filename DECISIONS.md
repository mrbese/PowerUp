# Decisions

Product decisions in order, with the team member who made the call. Code commits in this repo are authored "Claude" because the code was written with Claude Code; the decisions were made by the people named below. This log was compiled from Omer's sessions, so it holds his and Enqi's recorded decisions; teammates, add rows for yours. Times are Pacific (PDT).

| When | Decision | Made by |
|---|---|---|
| Fri Oct 16, 3:24 PM | Enter the Energy and Grid track (Base Power) | Omer |
| Fri Oct 16, 8:47 PM | Drop storms as the scenario; Los Angeles has none | Omer |
| Fri Oct 16, 8:51 PM | Prepare the fleet for wildfire shutoffs, Medical Baseline homes first, with a human in the loop | Omer |
| Fri Oct 16, 8:54 PM | Propose neighborhood microgrids that share home batteries during shutoffs | Omer |
| Fri Oct 16, 9:06 PM | Use a neighborhood mesh with a Starlink uplink when batteries lose cell service | Omer |
| Fri Oct 16, 10:15 PM | Replay the real October 2026 Malibu shutoff instead of an invented scenario | Omer |
| Fri Oct 16, 10:27 PM | Use SCE's Q4 2025 usage data | Omer |
| Fri Oct 16, 11:03 PM | Run a prior-art check against Base Power and SCE | Omer |
| Fri Oct 16, 11:17 PM | Fill batteries in risk tiers by priority (the ladder) | Omer |
| Fri Oct 16, 11:25 PM | Dispatch EVs only with human approval | Omer |
| Sat Oct 17, 11:59 AM | Price readiness on real Q4 2025 SCE-area wholesale prices | Omer |
| Sat Oct 17, 1:47 PM | Build the neighborhood island software layer with opt-in and opt-out, scoped to SCE in Malibu | Omer |
| Sat Oct 17, 1:49 PM | Name the repo PowerUp | Omer |
| Sat Oct 17, 1:51 PM | Combine the planner (Grace) and the guard (Interlock) into one entry | Omer |
| Sat Oct 17, 2:53 PM | Rename Grace to PowerUP | Enqi |
| Sat Oct 17, 4:36 PM | Frame the pilot around homes cut off because of the upstream line, not their own street | Omer |
| Sat Oct 17, 4:46 PM | Choose island candidates from line topology (last switch in series) | Omer |
| Sat Oct 17, 6:22 PM | Use Base Core batteries, given free to volunteer homes that share | Omer |
| Sat Oct 17, 6:33 PM | Pilot behind SCE switch RAR8848 (456 homes) | Omer |
| Sat Oct 17, 6:41 PM | Narrow the app to the pilot area; the startup owns the batteries | Omer |
| Sat Oct 17, 7:13 PM | Make the pilot the main app; keep the Malibu-wide app off GitHub | Omer |
| Sat Oct 17, 7:27 PM | Deploy 160 batteries at once; remove the fleet slider | Omer |
| Sat Oct 17, 7:38 PM | $9.99 emergency subscription for homes without a battery, 90% opt-in assumed | Omer |
| Sat Oct 17, 7:56 PM | Shutoff power at 2x the top residential TOU price for everyone; battery owners choose to sell or keep; solar sells | Omer |
| Sat Oct 17, 7:57 PM | Hosts use the bottom 20% of the free battery at the same price; the startup sells the rest | Omer |
| Sat Oct 17, 8:36 PM | State that PowerUP is a startup using Base hardware; islanding and grid-forming are stated assumptions | Omer |
| Sat Oct 17, 8:56 PM | The Interlock evening page replays Oct 14 on the pilot area only | Omer |
| Sat Oct 17, 8:58 PM | Remove the Australia and military packs | Omer |
| Sat Oct 17, 9:12 PM | Use industry-standard names for Interlock's eight checks | Omer |
| Sun Oct 18, 12:30 PM | Center the spoken pitch on islanding | Omer |
