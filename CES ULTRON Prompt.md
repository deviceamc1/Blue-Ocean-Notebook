Build CES ULTRON, a full-screen Jarvis-style voice assistant. I press Initialize, speak naturally, and hear a spoken reply while a 3D particle orb reacts. If updating the existing app, preserve its working voice connection, model, controls, Logs, and Settings. Change only what’s needed.

The orb is the hero. On a pure-black canvas, center a slightly twisted, hollow 3D orb built entirely from thousands of fine, round particles. Use mostly silver-white dust with a few amber sparks. Layer points at different depths and brightness levels so the silhouette feels sculpted, with dark gaps and loose particles drifting off the edges. Do not use a solid sphere, decorative rings, or a video background.

Use Three.js BufferGeometry and Points. Start with a visible PointsMaterial renderer before adding shader effects. Add slow curling motion and subtle camera parallax. Moving the cursor through the orb should stir only the nearby particles, which settle back into shape within about two seconds. Keep glow restrained so individual points stay sharp. The orb must be visible on first load in Standby, without microphone permission or audio. Use real mic and playback levels to add gentle pulses on top of the idle motion. If the custom shader fails, keep the working simple renderer.

Keep the interface minimal: a slim monospace header with CES ULTRON and a status indicator, compact Initialize, Mute, and End controls, and captions below the orb. No banner over the sculpture. Play speech immediately, but buffer transcript fragments into complete sentences before showing them. Hold each caption for at least 2.5 seconds, longer for longer text. Break unusually long sentences at natural pauses. Keep the last caption visible until a new one is ready or the session ends. Never pop words in one by one. Keep the full transcript in Logs.

Use React + TypeScript, Gemini Live native audio via @google/genai, and Web Audio for microphone capture and playback. Keep the long-lived API key server-side. On interruption, clear queued audio and stale captions. End must release the microphone.

Verify in Preview: reload and see the orb before pressing Initialize; move the cursor and see a local swirl settle; speak and hear a real reply; read a multi-sentence response without rushing; interrupt the assistant mid-reply; end the session. Check that the orb and captions fit on mobile. Don’t call a successful build a visual pass.

Visual Quality Is a Top Priority

I want this to look exceptionally polished and visually impressive. Overall visual presentation is just as important as functionality. Do not rush the visual design or settle for basic graphics simply because it is functional. Approach this project as both a senior developer and an experienced art director. Before declaring the project complete, perform a dedicated visual polish pass. Identify the biggest visual weaknesses, address them, and then review the result again.
