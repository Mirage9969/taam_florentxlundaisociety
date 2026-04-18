# Project name
Track Hoppers

## Problem Statement
Every day millions of people sit centimetres apart on buses and trains, staring at their phones in complete silence. Public transport is one of the last places where strangers are forced to share physical space — yet no one connects. Commuters have 10 to 40 minutes of dead time, every single day, with the people around them.
Transit operators like Skånetrafiken invest heavily in passenger experience — but nothing they offer today turns the journey itself into something people look forward to.


## Solution
Track Hoppers is a real-time co-op game that runs on passengers' phones during a journey. Players are trains moving along a network of circular tracks. One tap hops your train to a connected track. The goal is to work together to reach the centre track before the timer runs out — without colliding.

Scan a QR code, enter your name, and you are playing in seconds. No app install. No account. No tutorial. Just one button.
Rounds last 90 to 120 seconds — exactly the length of a stop-to-stop stretch. The game loops continuously so new passengers can join at any stop.

The key insight: strangers become teammates by design. You cannot win alone. You have to read what the other trains are doing and coordinate without speaking. That shared tension — and the shared relief when you make it — is the moment of connection.

**How It Works
Passenger scans QR code on the bus or platform
           ↓
Opens in mobile browser — no install required
           ↓
Enters name → assigned a train (shape + colour identity)
           ↓
Lobby fills with other passengers on the same journey
           ↓
Round starts — tracks appear on screen, trains move
           ↓
Tap to hop between tracks at switch points
Avoid collisions. Work together. Reach the centre.
           ↓
Round ends (120s or centre reached)
New round starts — anyone can join



Game Rules
One button. Tap the screen to hop your train to a connected track at the nearest switch point. There is a 0.6 second cooldown between hops.
Co-op by default. All players share the same objective: get at least one train to the centre track before time runs out. If any player reaches the centre, the round is a win for everyone.
Collisions eliminate. Two trains occupying the same track section at the same time — both are eliminated. Mid-hop collisions at switch points also eliminate both players.
The track graph. Each round generates 5 to 8 circular tracks in a procedural graph. Tracks overlap at switch points — the glowing amber dots where hops are possible.
Speed ramps. Trains accelerate as the round progresses. The longer the round goes, the harder it becomes to time hops correctly.
Edges open and close. Some switch points activate and deactivate dynamically, adding a puzzle layer on top of the reaction game.
Rhythm meter. When multiple players tap in sync, a shared rhythm meter fills. A full meter gives all surviving trains a brief speed boost.
Sudden death (optional). In the final 10 seconds, the goal track shrinks. If multiple players reach the centre simultaneously, the one who arrives first wins the round solo.


Lobby & Matchmaking

Perpetual open lobbies — join at any point, mid-ride
Rounds restart every ~2 minutes or on train departure
Minimum 2 players to start, maximum 8 per lobby
Players who join mid-round enter a queue and jump in at the next round start
3 second reconnect grace period for tunnel dropouts — your train holds position and you rejoin seamlessly


## Technical Approach



## Usage
