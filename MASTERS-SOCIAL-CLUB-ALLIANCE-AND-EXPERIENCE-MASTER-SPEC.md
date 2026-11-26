# MASTERS SOCIAL CLUB, ALLIANCE AND EXPERIENCE — MASTER SPEC

Status: OWNER APPROVED — November 26, 2026

Authoritative combined specification for Cut Throat Spades Masters. It replaces the earlier separate social and experience handoffs. The visual-board document (`OFFICIAL_23_DESTINATION_VISUAL_BOARD.md`) and the actual image assets remain as visual references; this master document does not replace those images.

This is an expansion to the existing project. Do not restart development, discard existing work or change approved gameplay rules.

## 1. Masters social network

A complete social and player-connection system. Players must be able to discover and connect with people they meet during gameplay.

Player discovery includes:

- Recent opponents.
- Player profiles.
- Friend requests.
- Private messaging.
- Player invitations.
- Player online status.
- Match history.
- Skill and sportsmanship endorsements.
- Player blocking and reporting.

After a Solo or Team match, players can select another player's profile and:

- Add Friend.
- Invite to Play.
- Invite to Room.
- Request Teammate Partnership.
- View Player Record.
- Send Message.

## 2. Room invitation system

Players must be able to invite other players into rooms where matches are being organized.

Support:

- Direct friend invitations.
- Recent opponent invitations.
- Teammate invitations.
- Multiple invitations.
- Private room invitations.
- Public room invitations.
- Invitation acceptance and rejection.
- Invitation expiration.

The invited player must be able to accept and enter the correct virtual room.

## 3. Two-minute reserved-seat invitations

Every available seat must support an invitation control represented by a PLUS (+) button.

When a host selects PLUS:

1. Display the available seat.
2. Allow the host to select a friend.
3. Send the friend an invitation.
4. Reserve the seat for two minutes.
5. Display a countdown.
6. If the friend accepts and connects, assign the seat to that friend.
7. If the timer expires, automatically fill the seat with an eligible AI opponent.
8. Allow the host to cancel or replace the invitation before the match starts.

The game must never begin with fewer than four occupied player positions.

AI seat replacement must be reliable and must not duplicate player identities or corrupt game state.

During an active hand, do not replace a human player with a friend. Handle seat transfers only at safe game boundaries under approved room rules.

## 4. Master Alliance partnerships

Players must be able to form partnerships with people they meet. Partnerships are the **Master Alliance**.

Support:

- Partnership invitations.
- Acceptance and rejection.
- Permanent friendships and partnerships (the Master Alliance).
- Temporary tournament partnerships.
- Partnership profiles.
- Combined statistics.
- Partnership history.
- Team rankings.
- Team achievements.
- Private team practice rooms.

Players may be physically located anywhere supported by the multiplayer service. They must be able to play on the same virtual team and at the same virtual table regardless of their physical location.

## 5. Team tournaments

Allow established partnerships to:

- Register for team tournaments.
- Enter private team competitions.
- Practice together.
- Track combined tournament records.
- Earn partnership rewards.
- Qualify for championships.

Enforce tournament eligibility, roster rules and fair-play requirements.

## 6. Cross-region team play

Support players connecting from different countries and geographic regions.

Requirements:

- Server-authoritative gameplay.
- Secure player authentication.
- Reliable synchronization.
- Reconnection handling.
- Latency monitoring.
- Regional matchmaking.
- Fair turn timing.
- Protected card information.
- Persistent match records.

Do not rely on client-side results for competitive scoring.

## 7. Ten approved Masters Experience features

Implement the following in prioritized development phases:

1. **Personalized Masters Entrance** — a player's own arrival into the club.
2. **Permanent Hall of Masters** — the lasting record of champions and legends.
3. **Player Rivalry and Rematch System** — tracked rivalries with rematch challenges.
4. **Rafael Torres Live Commentary** — live commentary on matches.
5. **Cinematic Replay Theatre** — watch and relive key hands and matches.
6. **Personalized Private Master Suites** — a player's own private room.
7. **Legendary Championship Rings and Legacy Rewards** — rings, titles and rewards tied to verified achievements.
8. **Adaptive Master AI** — AI opponents that adapt to the player's skill and style.
9. **World Championship Week** — the annual championship event.
10. **Masters Legacy Profiles** — a player's lasting competitive legacy.

## 8. Competitive integrity

Implement:

- Anti-cheat and secure server-side scoring.
- Hidden-card protection.
- Spectator mode.
- Skill-based matchmaking.
- Disconnect handling.
- Suspicious-play monitoring.
- Player reporting and moderation.
- Tournament integrity protection.

Spectators must never see hidden cards or interfere with live matches.

## 9. Luxury services

The social club takes place in the luxury penthouse defined by the visual board: interactive service NPCs and purchasable services in every destination.

- **Butler:** summoned, approaches the requesting player, takes requests, serves and clears on a tray, returns to position.
- **Bartender:** operates the bar, prepares selected drinks, serves.
- **Cigar attendant:** operates the cigar lounge, presents the menu and accessories, delivers purchased items.
- **Massage attendants:** operate the relaxation area, accept bookings, guide the player, perform the service, return.

Every purchase must display the price, identify the payment currency, require confirmation, deduct the correct virtual currency, record the purchase, and trigger the appropriate NPC interaction and animation. Use virtual currency and optional premium currency. Services must not affect competitive card fairness. Full specification: `OFFICIAL_23_DESTINATION_VISUAL_BOARD.md` §§3–4.

## 10. 23 World Tour destinations

Every destination is a distinctive 3D room with its own atmosphere, soundtrack, ambient sounds, furniture, lighting and architectural identity — not wallpaper swaps. All 23 support the same core systems: four players, the approved rules, competitive AI, card animations, service NPCs, purchasable services, profiles and rankings, tournaments.

1. Paris — French luxury penthouse, Eiffel Tower views, warm gold lighting.
2. London — Contemporary British private club, dark wood, leather, modern British luxury.
3. Rome — Italian palazzo-inspired gaming salon, marble, warm Mediterranean lighting.
4. Cairo — Luxurious modern Egyptian residence overlooking the pyramids, contemporary gold finishes.
5. Tokyo — Modern Japanese penthouse, dramatic skyline, refined minimalism.
6. New York — Manhattan sky residence, panoramic skyscraper views, dramatic nighttime lighting.
7. Las Vegas — Exclusive high-rise private gaming suite, spectacular city lights.
8. Venice — Elegant Venetian palazzo, canal views, historic character with modern luxury interiors.
9. Dubai — Ultra-modern sky palace, Burj Khalifa views, expansive glass architecture.
10. Rio — Elevated Brazilian luxury residence, coastal and city views, tropical design.
11. Sydney — Harbour-facing luxury residence, Opera House views, modern Australian architecture.
12. Moscow — Grand contemporary luxury salon, dramatic details, rich materials, winter city atmosphere.
13. Mumbai — Modern Indian luxury residence, skyline views, rich textures.
14. Hong Kong — High-rise luxury suite, Victoria Harbour views, illuminated skyline.
15. Athens — Contemporary Greek luxury residence, Acropolis views, stone and marble.
16. Switzerland — Alpine luxury chalet, panoramic mountain views, fireplace, warm wood and stone.
17. Caribbean — Private tropical estate, ocean views, open-air luxury lounge, palms.
18. New Orleans — Refined French Quarter-inspired private salon, wrought-iron details, jazz atmosphere.
19. Marrakech — Modern Moroccan palace lounge, intricate craftsmanship, courtyards, rich textiles.
20. Singapore — Futuristic luxury sky residence, Marina Bay views, dramatic illuminated gardens.
21. Antarctica — Extraordinary heated glass luxury research residence, ice landscapes, glaciers, aurora views.
22. Lunar Outpost — Luxury lunar residence, panoramic views of the Moon's surface and Earth.
23. International Space Station — Extraordinary luxury orbital lounge, Earth visible through panoramic windows.

For every destination, the production deliverables are: environment design, 3D room scene, four-player table arrangement, service NPC placement, interactive service areas, lighting and material specifications, environmental animations, destination-specific sound and music, and a working integration plan.

## 11. Technical implementation

Before development:

1. Audit existing GitHub systems.
2. Identify existing social, room and multiplayer functionality.
3. Reuse existing working code.
4. Identify missing functionality.
5. Produce the integration plan.

Implement in phases:

- Player identity and profiles.
- Friends and messaging.
- Room invitations.
- Two-minute reserved seats.
- AI seat filling.
- Partnership formation (Master Alliance).
- Team matchmaking.
- Team tournaments.
- Spectator system.
- Advanced Masters Experience features.

The engine is currently client-side. Server-authoritative gameplay, hidden-card protection and secure scoring (sections 6 and 8) require a real backend (Supabase Edge Functions / Realtime / RLS) — that is a dependency, not a UI task. Do not rely on client-side results for competitive scoring.

## 12. Testing

Test:

- Inviting a friend from an active room.
- Accepting a room invitation.
- Rejecting an invitation.
- Invitation timeout.
- Two-minute seat reservation.
- AI filling an expired reserved seat.
- Friend joining before a match starts.
- Friend joining from another country.
- Forming a partnership.
- Playing as remote teammates.
- Entering a tournament together.
- Disconnecting and reconnecting.
- Spectator hidden-card protection.
- Blocking and reporting players.

## Design philosophy

Reputation > Luck > Money.

Cut Throat Spades Masters must allow players to meet through competition, recognize talent, build partnerships and create lasting competitive legacies.

The goal is not simply to play a hand of Spades.

The goal is to build a worldwide community of Masters.
