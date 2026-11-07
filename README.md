# Mossmaze 1.0 TEST
Native Java/Canvas Android 8+ Nurimaze room-shading puzzle.

Tap a room to shade or clear it. Every room is entirely dark or white. All white cells connect without any loop. No 2x2 square can be entirely dark or entirely white. S, G, O circles and triangle rooms stay white. The unique S-to-G route must pass through every circle and no triangle. White dead-end branches are allowed. Twelve distinct 4x4 room layouts each have a different unique solution.

Saved moss palette and cell guides, GG007 icon/menu/site/privacy, unlimited undo/reset. Offline, no ads, analytics, account or requested permissions. Settings and completed-puzzle marks stay on device. External studio link opens browser.

Independent Java DFS-cycle and explicit route-list checks agree with production edge-count and BFS-parent checks on all 65536 tile shadings per puzzle, including shadings that violate room boundaries. Unique solutions, symbol room locks, bounds, solve, undo and replay pass. Adapter navigation, saved settings, privacy, room taps, next, levels and persistence pass. Actual drawing pixels inspected, not phone screenshots. Phone runtime, performance and browser handoff QA incomplete. Signed TEST only, not final or Play published.

Current 803-entry registry, 118 partial recovered README records and exact Twincedar cumulative stage found no Nurimaze match. Roomhaven and Clearingfen also combine room constraints with connected white cells, but use room quotas or clearing limits and straight-run border counts, not an acyclic white maze with circle-on-route and triangle-off-route constraints. Fernshore specifies all dead ends with circles; Mossmaze allows unlabeled dead-end branches and uses two endpoints plus on/off-route symbols. Cloverroad draws a single loop with room visit quotas rather than shading a white tree. Known Nurimaze genre, not a global invention. Partial corpus, not ALL-local. Rules: https://www.nikoli.co.jp/en/puzzles/nurimeizu/ and https://www.cross-plus-a.com/html/cros7nrmz.htm .

Download signed test APK on MEGA: https://mega.co.nz/#!lNV1hDBD!DFYTZM0Z0uy2db5agKDkGBS59OkTAT-M8wYHsVhObXM

APK SHA256: 9a2fd856f71ae958cb6dd2db6ab4947ce09345ccd8e8d6436ef5b1819970e9d7
Full Git source upload remains pending; source is preserved in the private archive.
