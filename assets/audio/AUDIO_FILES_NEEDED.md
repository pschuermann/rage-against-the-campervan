# Audio Files Needed

This document lists all the audio files required for "Rage Against the Campervan".

## Required Audio Files

Place all audio files in the `assets/audio/` directory with the exact filenames listed below.

### Music Files (MP3 format recommended)

#### 1. menu-music.mp3

- **Purpose**: Background music for the menu screen
- **Style**: Upbeat, road trip vibe, nostalgic
- **Loop**: Yes (should loop seamlessly)
- **Duration**: 30-90 seconds
- **Volume**: Will be played at 50% (0.5)
- **Suggestions**:
  - Upbeat acoustic guitar
  - Road trip vibes
  - Cheerful, adventure-themed
  - Think: classic road movie soundtrack

#### 2. game-music.mp3

- **Purpose**: Background music during gameplay
- **Style**: Driving music, energetic but not too intense
- **Loop**: Yes (should loop seamlessly)
- **Duration**: 60-120 seconds
- **Volume**: Will be played at 40% (0.4)
- **Suggestions**:
  - Steady rhythm matching driving pace
  - Energetic but focused
  - Build tension without being overwhelming
  - Electronic/synth or rock guitar

### Sound Effects (MP3 format recommended)

#### 3. crash.mp3

- **Purpose**: Player collision with vehicles
- **Style**: Crash/impact sound
- **Duration**: 0.5-1 second
- **Volume**: Will be played at 60% (0.6)
- **Suggestions**:
  - Car crash/impact
  - Metal crunching
  - Not too loud/harsh

#### 4. explosion.mp3

- **Purpose**: Rocket hits campervan
- **Style**: Explosion effect
- **Duration**: 0.5-1.5 seconds
- **Volume**: Will be played at 70% (0.7)
- **Suggestions**:
  - Satisfying explosion boom
  - Not realistic war explosion
  - More arcade/game-like
  - Punchy and rewarding

#### 5. rocket-fire.mp3

- **Purpose**: Launching a rocket
- **Style**: Whoosh/launch sound
- **Duration**: 0.3-0.7 seconds
- **Volume**: Will be played at 50% (0.5)
- **Suggestions**:
  - Rocket launch whoosh
  - Quick "fwoosh" sound
  - Satisfying but brief

#### 6. overtake.mp3

- **Purpose**: Successfully passing a campervan
- **Style**: Positive feedback, success sound
- **Duration**: 0.3-0.5 seconds
- **Volume**: Will be played at 50% (0.5)
- **Suggestions**:
  - Positive "ding" or "chime"
  - Success notification
  - Rewarding but not annoying
  - Think: achievement unlocked

#### 7. collect.mp3

- **Purpose**: Picking up power-up boxes
- **Style**: Pickup/collect sound
- **Duration**: 0.2-0.4 seconds
- **Volume**: Will be played at 50% (0.5)
- **Suggestions**:
  - Classic game pickup sound
  - "Bloop" or "bling"
  - Retro game style
  - Quick and satisfying

## Where to Get Free Audio

### Music

- **FreeMusicArchive** (freemusicarchive.org)
- **Incompetech** (incompetech.com) - Kevin MacLeod's royalty-free music
- **Bensound** (bensound.com)
- **Purple Planet Music** (purple-planet.com)

### Sound Effects

- **Freesound** (freesound.org)
- **Zapsplat** (zapsplat.com)
- **Mixkit** (mixkit.co/free-sound-effects/)
- **OpenGameArt** (opengameart.org)

## Format Requirements

- **Format**: MP3 (most compatible)
- **Bit rate**: 128-192 kbps is fine for games
- **Sample rate**: 44.1 kHz standard
- **Channels**: Mono or Stereo

## License Considerations

Make sure any audio you use is:

- Royalty-free
- Licensed for game use
- Properly attributed if required

## Testing

Once you add the audio files:

1. Run the game with `npm run dev`
2. Check browser console for any loading errors
3. Test all sound effects in-game
4. Adjust volumes in the code if needed (edit GameScene.js and MenuScene.js)

## Fallback Behavior

The game will work without audio files! If files are missing:

- Loading errors are logged to console (warnings only)
- Game continues without sound
- No crashes or breaking issues
