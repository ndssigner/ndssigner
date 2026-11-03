Bitcoin signers and seed backups built from cheap, old or unexpected hardware.
Everything here is air-gapped, open source and early. Read the code before you
trust it, and don't put funds on the alphas.

| Project | What it is | Latest |
| --- | --- | --- |
| [dtmf-signer](https://github.com/ndssigner/dtmf-signer) | A signer you build on a breadboard around a Raspberry Pi Pico. It hears PSBTs as phone tones and never shows the seed | v0.2.0-alpha |
| [nds-signer](https://github.com/ndssigner/nds-signer) | SeedSigner's code on a Nintendo DSi, with QR through the camera or phone tones | v0.2.2-alpha |
| [ur-tones](https://github.com/ndssigner/ur-tones) | The tone format both signers speak: UR parts as DTMF, over a cable or through the air, plus a web tool for Sparrow | v0.4.0 |
| [seedcraft](https://github.com/ndssigner/seedcraft) | Seed backups as beads, bricks or cards, readable by software or by hand with a pencil | v1.0.1 |

## Why

I don't think self-custody should mean buying a device that screams "Bitcoin"
and gets shipped to your address. So everything here either borrows hardware
that already lives another life, or uses generic parts you put together
yourself.

A Nintendo DSi in a drawer looks like an old toy, not a wallet. A seed kept
as beads looks like a necklace. That kind of plausible deniability is also
cheap: a used DSi costs around $50, and a Pico build about $13 in parts.

Building it yourself, or reusing something nobody would bother to tamper
with, is the best answer I know to supply-chain attacks like the Ledger
implant of 2026. DTMF-Signer goes a step further: the seed never shows on
its screen, and it has no random number generator that could fail.

And I like old machines. Data that travels as sound needs no camera and no
network, so a cassette, an MP3 player or, one day, an HP 48 or a Commodore 64
can be part of the chain.

These are weekend projects: alpha, unaudited, and open to anyone who wants
to help or take them further.

The most useful thing you can send is a review: open an issue, or find me on
[Stacker News](https://stacker.news/ndssigner) and Nostr
(`npub1n2yw95vqalqzckdnks4sedzyyjg75lasmfntt8xlecdnnwza7kkqn84hjz`).
