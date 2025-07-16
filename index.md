---
layout: page
title: Home
page_title: Shields Up! Software Radiation Protection for Commodity Hardware in Space
hide_title: true
permalink: /
---

ShieldsUp is a set of two software systems that protect against the two most prevalent single-event effects facing spacecraft operators today: single-event latchups and single-event upsets.
Our system increases the reliability of commodity hardware and enables them to act as reliable flight computers or co-processors on spacecraft.
This system is tested in real-world systems, from commodity SmallSats to a commodity compute element onboard the Perseverance Mars rover.

> The 9000 series is the most reliable computer ever made. No 9000 computer has ever made a mistake or distorted information. We are all, by any practical definition of the words, foolproof and incapable of error.

*- HAL, 2001: A Space Odyssey*

##### Hold up, radiation errors?

Yes! On Earth, we're protected by the Earth's magnetic field and atmosphere, which deflects or absorbs most of the ionizing radiation from the sun.
However, spacecraft in orbit or deep space don't have the same protections, and are exposed to heavy amounts of ionizing radiation, which can cause all sorts of nasty errors on the satellites.
We call transient errors that cause the computer to misbehave *single-event effects*.

#### Single-Event Upsets

The most common single-event effect we see in space are *single-event upsets* (SEUs), which are essentially radiation-induced bit-flips in memory, cache, or the compute pipelines.

#### Single-Event Latchups

The residual charge left by radiation particles can change transistor structures and cause a localized short-circuit known as *single-event latchups* (SELs).
This causes the short-circuited area to generate a ton of heat.
And in space, you don't have an atmosphere for the heat to dissipate into, so the heat eventually overheats and destroys the chip.
Fortunately, as long as we can detect these latch-ups, we can simply power cycle the affected chip before it burns out.
This draws out the residual charge that caused the latchup in the first place, and the chip will work like normal again.


