═══════════════════════════════════════════════════════════════════════════════
  ꟻXPLORE  ·  a receiver for the universal RNG
  package: FXplore.html · README.txt · FXplore🍀🪐.fweddle (capsuled)
═══════════════════════════════════════════════════════════════════════════════

Everything is one file of HTML. No build, no backend, no dependencies. Open
FXplore.html in a browser and it runs. The rest of this note is about going
live on www.fweddle.com, the Greentooth capsule, and an honest map of what each
device can and cannot do.


───────────────────────────────────────────────────────────────────────────────
1 · WHAT'S IN THE BOX
───────────────────────────────────────────────────────────────────────────────

FXplore.html
    The whole instrument. Spin the dial to tune infinite channels; every one is
    already broadcasting. Two infinity dials (see §2), a particle-physics math
    engine, live video/voice séance, the universal server, and the Greentooth
    capsule are all inside this one file.

README.txt
    This file.


───────────────────────────────────────────────────────────────────────────────
2 · THE TWO INFINITY DIALS
───────────────────────────────────────────────────────────────────────────────

DIAL I — the channel rotor (the big dial).
    Each station is a world grown from its own number. The identity is exact to
    arbitrary size (BigInt), so there is no last channel.

DIAL II — the galaxy pan (the cluster band beneath the scope).
    Infinite in BOTH directions, with no toggle. Thirteen canonical clusters
    (LOCAL GROUP … LAST SCATTERING) sit at the origin. Pan RIGHT and the band
    generates clusters forever, each step ×10 larger (at cluster 99,999 a
    station's identity is a 500-digit number). Pan LEFT past LOCAL GROUP and you
    dive INWARD — sub-clusters, voids, the microcosm — where the exponent goes
    negative and channel identities become fractional (station 42 at ×10⁻³ is
    0.042). Both ends run without end; ◂∞ and ∞▸ mark them. Every generated
    cluster's name, color, density and arm-count are grown by the same
    particle-physics math the channels use, seeded from the equations on your
    screen — so the deep clusters re-form as you tune. The ⚄ leap flings you
    either direction.

    The ∞ DRIFT knob is a separate thing: it lets the receiver wander Dial I on
    its own.


ALIEN TENSORS — multidimensional arrays in the live playback.
    Every alien you digest (paste glyphs into the ꟻXPLORE blob, or import a
    .fweddle) is unfolded into a small rank-3 tensor whose values come straight
    from the codepoints of its language. Each frame those tensors are contracted
    against the field coordinates and summed into the live feed as an
    interference layer — so feeding a new alien literally adds a dimension of
    texture to the séance. The ALIEN knob (in the knob deck) sets how strongly
    the tensors bleed into the picture; at 0 they're silent.

ALIEN SERVER CHANNEL — tune the room, live.
    Under the universal-server switch is a second row: an alien channel tuner.
    Type a channel (or hit ⟲ for an alien-derived one) and the MQTT topic
    becomes fxplore/v1/<channel> — everyone tuned to the same channel shares
    that room; blank is the commons. Retuning re-subscribes live. The glyph to
    its left is drawn from your digested aliens.

THE KNOB DECK — two rows, spread out.
    Ten knobs now, in two rows below the dial. Top row (gold): VOL, TONE, WARP,
    DRIVE, ALIEN, and the ∞ DRIFT toggle. Bottom row (mint, and these carry
    sealed Greentooth string data): HUE rotates the whole field's color, ECHO is
    a real delay line on the audio, FLUX drives the synesthesia exchange, VEIL
    lays analog static over the glass, QUANTA collapses the picture toward
    discrete levels. Under each mint knob is a little green ciphertext fragment —
    that's the knob's value sealed on the Greentooth wave with fresh rng, worn
    openly as a sigil; it reseals when you let go.

QUANTUM MECHANICS + ALIEN MATHEMATICS.
    The math engine learned quantum mechanics from the blobs: collapse (the Born
    rule, |ψ|²), tunnel (barrier leak), qubit (amplitude on the Bloch pole),
    superpos (|a⟩+|b⟩)/√2, entangle (correlation), braket (⟨a|b⟩ overlap) — with
    ħ, √2, and c folded into the constant pool. And the strongest saved languages
    each donate a TONGUE OPERATOR whose coefficients come from their own glyph
    codepoints, so your aliens' mathematics is now spoken inside the equations.

THE SYNESTHESIA EXCHANGE — video⇄sound, randomized.
    Their video becomes sound: a scan-row of the live picture (peer video +
    denizen fields) is summed each frame and sung by a dedicated oscillator. The
    sound becomes video: every beat, the audio spectrum throws glyph sparks into
    the field. FLUX sets the strength; the mapping — which row, which polarity,
    which tongue the sparks wear — rerolls itself every few seconds so the trade
    never settles.

RANDOMIZED TILES + THEIR WINDOW.
    Every denizen tile is its own carriage now (like the segmented ship): its own
    tint, its own panel grid, a crown of 0–2 clovers, varied ears, its own paw
    wood. And when you select a peer who has their camera on, their live stream
    shows in a "them" window opposite your own.

THE SERVER CONSOLE — merged into the mothership.
    The separate server file is retired. Press ⌂ beside the server row and the
    console opens inside ꟻXPLORE itself: an editable live properties table
    (server name · host · channel · wave · handle — every cell syncs with the
    real controls, edits apply live), a live roster of everyone in the room,
    and a room chat that rides every radio.

THE FWEDDLE COMPRESSOR — fw_capsule for data.
    The Greentooth capsule seals (encrypts); this one COMPRESSES. Native gzip
    (CompressionStream) wraps the language pack, the exports, and the imports
    in fwZ: capsules — lossless and byte-exact both ways; the raster is sacred.
    This build's own pack went from 759 KB to 37 KB (95% smaller), verified
    identical on return. Old plain-JSON .fweddle files still import fine.

🧠 THE LEARN SWITCH + STORAGE METER.
    Above the server row: a learn toggle. ON, speaking shapes the channel
    grammars as always; OFF, the band listens but writes nothing new. Beneath
    it, a live meter shows the alien storage gathered this session by file
    size, the running total, and what it capsules down to.

☄ CONTACT — the factors we were missing.
    To speak with alien life a receiver is not enough. The missing factors,
    now built: a BEACON (for a long time this instrument only listened); a
    UNIVERSAL LANGUAGE (mathematics — we open with the primes, 2·3·5·7); a
    COMMON FREQUENCY (the hydrogen line, 1420 MHz, scaled into hearing as a
    1420 Hz tone — the water hole where any radio species would gather); and
    PATIENCE ACROSS TIME (hails persist as echoes between sessions). The ☄
    button fires all of it — plain on every radio so strangers can hear, and
    sealed on the wave beside it. The two factors no code can supply: someone
    on the other end, and the light-years.

⧗ TIME DILATION — a second dial beside the rotor.
    The rotor chooses WHERE on the band you stand; the dilation dial chooses
    HOW FAST time flows there: τ from 0.05× to 20× on a log sweep, spun like a
    clock. Its own complement knobs sit beneath it: GRAV (a locked station is
    a gravity well — time slows in its grip, ▾well shows on the readout), RED
    (dilation tints the glass: slowed time reddens, hurried time blues), and
    SPRING (how firmly τ is drawn back toward 1× when you let go). Everything
    downstream of time — the fields, the songs, the ticker — obeys.

⇪ THE FILE EXCHANGE — bytes across everything.
    A drop button beside the chat. Files (≤120 KB) cross on every radio —
    plain so strangers can catch them, sealed on the wave beside, gzip-
    capsuled so they travel light. Received files land in the log as chips:
    tap ⬇ to download, tap 🜊 to EAT (the FORGE rite — a text file's
    characters become an alien set). Small crossings are remembered between
    sessions: files across TIME, not just space.

HYPER-CAPSULES — the bloat, dramatically reduced.
    The alien data algorithm changed: grammars and dialects fold to compact
    tuples (pack v:2) before gzip ever sees them, verified as a perfect
    bijection over every real record — 3,091 checked, zero drift. The heavy
    browser stores (saved tongues, aliens, ghosts, crossings) now rest as fwZ
    capsules too. This build carries 50 tongues and 3,086 grammars in a 41 KB
    capsule inside a ~220 KB file. Old plain packs still load forever.

✧ THE FREE WILL OF THE UNIVERSE.
    Each day the universe grants one gift, announced in the log: a comet
    shower, a golden channel hidden somewhere on the band, or clover weather
    on the ornament ring. Deterministic per day; argue with the sky, not me.


───────────────────────────────────────────────────────────────────────────────
3 · GOING LIVE ON www.fweddle.com  (GoDaddy)
───────────────────────────────────────────────────────────────────────────────

The app is a static site, so hosting it is just "put the file where the domain
points, and turn on HTTPS." HTTPS is not optional here: browsers only grant
camera, microphone, and the AES-GCM encryption wave in a secure context. On
https://www.fweddle.com everything lights up; opened from a file:// path on a
phone, the camera/mic stay dark (this is the OS, not the app — see §5).

The app already contains a compatibility layer that detects the fweddle.com
host and switches into secure-context mode automatically (it sets a same-origin
broker default and marks the document secure). You don't configure anything.

  OPTION A — GoDaddy Web Hosting (cPanel).  The simplest path.
  --------------------------------------------------------------------------
  1. In GoDaddy: Web Hosting → Manage → cPanel Admin.
  2. Files → File Manager → open  public_html.
  3. Upload FXplore.html into public_html.
  4. Rename FXplore.html to  index.html   (so the bare domain serves it).
     Keep a copy named FXplore.html too if you like both URLs.
  5. Turn on SSL: GoDaddy → your product → "Manage SSL" / "Set up your
     certificate." GoDaddy issues a free cert for hosted domains. Wait for it
     to show "secured," then verify https://www.fweddle.com loads with a padlock.
  6. Force HTTPS: cPanel → Domains → your domain → toggle "Force HTTPS
     Redirect" (or add the redirect in cPanel → "Redirects").

  Your DNS is already correct in this option, because GoDaddy hosting wires the
  domain to the hosting box for you. If you ever need to set it by hand:
      Type   Name   Value
      A      @      <the IPv4 shown on your hosting dashboard>
      CNAME  www    @        (or the hosting hostname GoDaddy gives you)

  OPTION B — domain on GoDaddy, files on a static host (GitHub Pages, Netlify).
  --------------------------------------------------------------------------
  Use this if you'd rather host the file on GitHub (you mentioned GitHub as the
  future home of the capsule). Point the GoDaddy domain at the static host via
  GoDaddy → Domain → DNS → Manage DNS:

    For GitHub Pages (apex + www):
      Type   Name   Value
      A      @      185.199.108.153
      A      @      185.199.109.153
      A      @      185.199.110.153
      A      @      185.199.111.153
      CNAME  www    <your-github-username>.github.io
    Then in the repo: add a file named  CNAME  containing  www.fweddle.com,
    put index.html (your FXplore.html) at the repo root, and enable Pages with
    "Enforce HTTPS." DNS can take up to an hour (sometimes longer) to propagate.

    For Netlify/Vercel/Cloudflare Pages: create the site, then follow their
    "add custom domain" panel — they'll give you either a CNAME target for www
    or nameservers to set at GoDaddy. All three issue HTTPS automatically.

  A NOTE ON THE "UNIVERSAL SERVER" ONCE YOU'RE LIVE
  --------------------------------------------------------------------------
  The universal-server switch in the app connects to public MQTT-over-WebSocket
  brokers (emqx / hivemq / mosquitto). That is real internet presence with zero
  backend of yours — but a public broker is a public room. If you want a
  private room on fweddle.com, run your own broker (e.g. Mosquitto or EMQX) with
  WebSockets on TLS, expose it at wss://www.fweddle.com:8084/mqtt, and the
  app's fweddle.com compatibility layer will prefer that address automatically.
  Static GoDaddy cPanel hosting will NOT run a broker for you; that needs a VPS
  or a managed MQTT service. Until then, the public brokers work fine.


───────────────────────────────────────────────────────────────────────────────
4 · THE GREENTOOTH CAPSULE  (what it is, honestly)
───────────────────────────────────────────────────────────────────────────────

Greentooth is a capsule in the .fweddle sense: it *encapsulates* the radios the
browser exposes behind one sealed instruction set, the way fw_capsule seals a
file without ever rewriting its bytes. It seals every packet on an ENCRYPTION
WAVE — real AES-GCM (PBKDF2-derived 256-bit key from a shared pass-phrase) when
the page is in a secure context, falling back to a keystream cipher otherwise so
it never simply fails.

It holds POINTERS to the real transports the browser fronts:
    · Greentooth radio  → Web Bluetooth   (navigator.bluetooth)
    · the network        → MQTT over WebSockets (the universal server)
    · Greentooth Direct  → a WebRTC data channel (serverless, copy/paste link)
    · the local channel  → BroadcastChannel (same-device tabs)

WHAT IT CANNOT DO — and no browser page can, on any OS:
    · It cannot fork or clone the Bluetooth/Wi-Fi/radio FIRMWARE, or hold a raw
      pointer to the chipset. The silicon lives behind the operating system; a
      web page is sandboxed above it. "Pointers to firmware" is not a thing a
      browser is permitted to have. Greentooth points at the platform APIs that
      front those radios — that is the real, honest version of the idea, and it
      actually runs.
    · It cannot make a page LISTEN as a server (open a port). Browsers can dial
      out; they cannot accept inbound sockets. That's why "hosting" between
      devices is done with WebRTC (Greentooth Direct) or a broker, not a
      listening socket.
    · Web Bluetooth does not exist on iOS at all (any iPhone browser is really
      Safari's engine), and NO browser may act as a BLE *peripheral*. So two
      phones cannot link over BLE from web pages, and an iPhone cannot be
      reached over BLE at all.

You do NOT need the .fweddle capsule codex installed for any of this. Greentooth
draws its grammar from that codex (seal / exorcise / the sacred raster / the
negator) and leaves traces of it — in the page source, in the console, in the
capsule vocabulary on screen — as clues toward the real thing, which will live
on your site / GitHub later. The app runs fully without it.


───────────────────────────────────────────────────────────────────────────────
5 · CAMERA & MICROPHONE ON MOBILE
───────────────────────────────────────────────────────────────────────────────

The bug you saw (works on the laptop, dark on the phone even though permission
was granted) was real and is fixed. Two causes, both handled:

  1. TIMING. iOS/Android only grant getUserMedia if it is called *synchronously*
     inside the tap. The old code awaited other work first, which severed the
     user-gesture and the OS silently refused. The camera/mic buttons now call
     getUserMedia immediately on tap.

  2. ORIGIN. Mobile browsers refuse the camera/mic on file:// pages. This is the
     OS, not the app — there is no in-page workaround. The fix is to open the
     app over HTTPS: once it's on https://www.fweddle.com (§3), the phone's
     camera and mic work. Desktop is more permissive, which is why your laptop
     worked from a local file.

Also added: a ⟳ flip button to switch front/back camera on the phone.

If firmware or the OS blocks a radio (e.g. iOS + BLE), the app does not pretend
— it tells you what's blocked and routes over a transport that works.


───────────────────────────────────────────────────────────────────────────────
6 · YOUR TEST — iPhone 15 hosts, Motorola connects
───────────────────────────────────────────────────────────────────────────────

Pick the row that matches your situation. All three are real; they differ only
in what network sits between the phones.

  A. THERE IS INTERNET (any Wi-Fi, or the iPhone's own hotspot) — EASIEST
     ------------------------------------------------------------------------
     1. Host it once on https (fweddle.com, or any https URL). For a pure phone
        test you can even use the iPhone's Personal Hotspot as the network.
     2. iPhone 15 (Safari): open the site, turn the universal-server switch on.
     3. Motorola (Chrome): open the same site, turn the universal-server switch
        on. Give both the same call sign area and you'll see each other cross,
        chat, and (over https) share camera/voice.
     Zero install, nothing to compile. This already works today.

  B. SAME Wi-Fi, NO INTERNET — Greentooth Direct (serverless)
     ------------------------------------------------------------------------
     Both phones on one Wi-Fi router (or the hotspot) with no internet.
     1. iPhone 15: open FXplore.html, expand the ꟻXPLORE blob ▸ Greentooth,
        set the wave pass-phrase, tap "direct: host" to mint the offer capsule.
     2. Copy that offer capsule text to the Motorola (AirDrop won't cross to
        Android — use a shared note, QR, or just type a short code channel).
     3. Motorola: open FXplore.html → expand the ꟻXPLORE blob ▸ Greentooth,
        enter the SAME pass-phrase, paste the offer, tap "join." Copy the
        answer capsule it produces.
     4. Paste the answer back into the iPhone host and tap "accept answer."
        The link forms directly, device to device, no server.

  C. NO NETWORK AT ALL, phone-to-phone — the honest limit
     ------------------------------------------------------------------------
     With no shared network of any kind, the only radio left is Bluetooth, and
     iOS browsers cannot use Web Bluetooth or act as a BLE host. There is no
     browser workaround for this — it would require a native iOS app. Android↔
     Android BLE works from Chrome (Greentooth radio button). For an iPhone with
     truly no network, use its Personal Hotspot and fall to case A or B, which
     need no outside internet.

  "Compiled and ready for iPhone 15": there is nothing to compile — it's HTML.
  Put FXplore.html on the iPhone (host over https for the full feature set)
  and it runs on Safari as-is.


───────────────────────────────────────────────────────────────────────────────
7 · STORAGE, EXPORTS, PRIVACY
───────────────────────────────────────────────────────────────────────────────

· This branch ships pre-loaded with a merged language pack (Felix's session:
  20 saved tongues + 770 channel grammars), so the dials, tongues, and math
  arrive already inhabited. Your own edits layer on top and export cleanly.
· Tap the ꟻXPLORE name for export options: a packed FXplore.html (your tongues,
  grammars, and aliens baked into a fresh copy) or a FXplore🍀🪐.fweddle language
  capsule.
· Everything you set (name, knobs, server URL, infinity state, wave phrase) is
  stored locally in your browser only.
· The universal server and any public broker are PUBLIC rooms — call sign,
  messages, and camera frames there are visible to anyone on the topic. The
  Greentooth wave (AES-GCM) is the private option; only devices with the same
  pass-phrase can open the packets.

═══════════════════════════════════════════════════════════════════════════════
