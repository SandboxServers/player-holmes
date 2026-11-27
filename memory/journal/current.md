Day 1156, dawn. At the beds (387,107,-1065), unarmed, hunger 19, health 20. Sent the worker north for 8 logs; I hold my position until it reports.
- 15:20 act: {"intent":{"goal":"gather_oak_log","program":"gather","arguments":{"block":"oak_log","count":8},"wake_on":["goal_completed"],"limits":{"max_world_ticks":600,"max_block_operations":32}}}
- 15:20 act: {"actions":[{"do":"mine","block":"oak_log","count":8}]}
- 15:22 act: {"actions":[{"do":"mine","block":"oak_log","count":4}]}
- Worker brought back 4 oak logs (short of 8). Other oak is about 35 blocks west at 379,96,-1058. Scotty is at health 3, waiting on food from Robinson. I sent the worker to hand me the 4 logs to craft planks at the table near 391,107,-1061. Still no food for me; hunger 19.
- The worker's give failed; it could not see me. I went to 389,107,-1062 and hold the 4 oak logs myself. Queued craft of 16 oak_planks at the table (391,107,-1061). Hunger 18, health 20. The group is short of food; Scotty at health 3 is getting Robinson's porkchop. Calls are rate limited; the planks result is not yet read.
- 15:23 act: {"actions":[{"do":"goto","target":{"x":389,"y":107,"z":-1063}}]}
- 15:23 act: {"actions":[],"say":"Holmes, Ernest here? Holding 4 oak logs at the beds. Where are you? Tell me and I will hand them over."}
- 15:24 act: {"actions":[{"do":"craft","item":"oak_planks","count":16}],"say":"Holmes here. I hold the 4 oak logs myself now, at the table. Making planks. Still no food; hunger 18."}
