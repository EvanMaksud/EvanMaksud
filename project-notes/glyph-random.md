# Glyph Random

An experimental Nothing Phone glyph-light app.

## Summary

This Stage 1 app explores the Nothing Glyph Developer Kit by creating sparse randomized light patterns. It opens a simple foreground app with start/stop controls and avoids invasive permissions.

## Features

- Start and stop random glyph scenes.
- Registers with Nothing's official Glyph Developer Kit.
- Randomly selects glyph channels and timing.
- Uses soft fade curves where supported.
- Sends per-channel intensity values where the SDK accepts them.
- Keeps scenes sparse to avoid harsh strobe-like behavior.
- Uses only the glyph-enable permission.

## Stack

- Android
- Nothing Glyph SDK
- ADB testing

## What I Learned

- How device-specific SDKs shape app design.
- How to keep an experimental hardware app permission-light.
- How small interaction details affect the feel of lighting patterns.

