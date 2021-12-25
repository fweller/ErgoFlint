# ErgoFlint
The keyboard that finds the middle path between ergonomics and familiarity

# Why did I start this project?
Because I could not find a keyboard that was perfect for me

# Goals for this project

## Primary Goal
To be as ergonomic as possible while also being incredibly easy to switch back and forth with traditional staggered keyboards.
A common issue when using unusual keyboard shapes is that we still have to type on a laptop keyboard once in a while.

## Secondary Goal
To adapt to the key count preferences of the individual user, and continue to be useful for that user as preferences change. 
- use the entire keyboard today, stretch your fingers to reach the keys at the extremes, just like you would on a laptop keyboard.
- or use only the alpha character portion of the keyboard, reduce finger travel, rely on modifier keys, be as minimal as possible such as a Dactyl Manuform 4x6 or a Kyria.
- or something in between extremes;  Perhaps you don't want to reach for the function keys, so you overload the number keys.  Or perhaps you don't want number keys either, so overload the alphas to act as your number pad.

## Ergonimic Goals
- **Columnar Stagger** - Minimize ulnar and radial deviation (sidewise bending) that comes with traditional keyboard stagger.  And avoid the awkwardness of a pure ortholinear layout.
- **Wrist Rest** - Minimize wrist supination and pronation (extension and flexion) with a wrist rest that adjusts to your needs, not just a pad resting in front of the keyboard.  Think of something like a wrist rest in a Dactyl Manuform but designed for better adjustability.
- **Split keyboard** - Minimize forearm pronation by incorporating a split keyboard with easily adjustable tenting.  adjustable split keyboard allows the user to adjust each half of the keyboard for optimal tenting, so wrists can rest in the most neutral position.
- **Compact 75% keyboard** - Reduce strain on the forearm, neck, and shoulder by avoiding unnecessary arm stretching that comes from using a full size 100% keyboard.

## Implementation Details
- Mechanical key switches that are Cherry MX compatible.  Nothing else will do.
- Hot-swap sockets.  Because we like to change our switches with our moods.....I mean when they wear out.
- Thumb switches.  Not just for the space bar, but to give us easy access to modifier keys.
- Inner modifier switches.  Give users extra keys for whatever they come up with.
- Fancy keycaps.  Use most any popular keycap collection.  Special preference for SA or MT3 profile because these are the most amazing to type on.
- Flat keywells.  This may be less ergonomic than the concave keywell of a Dactyl Manuform, but flat keywells are much easier to build using rigid printed circuit boards.
- QMK software to easily reprogram the keyboard as needed.

## Future
- Incorporate a trackball 

# Status
Just getting started with this project. 
If UHK makes a columnar staggered version of their UHKv2 keyboard, I'll probably purchase that and quit this project.

# Files

- ergoflint.json This is the keyboard layout that can be viewed with the [keyboard-layout-editor](http://www.keyboard-layout-editor.com/)
- ergoflint.png is the printed output of the above.

# Keycap contention

Backspace is usually 2u in ANSI and ISO, but is 1u in Japanese and many ortholinear kits.
Delete is usually 2u in full size keyboards, but is 1u in ortholinear kits.
Pipe /Backslash "|\" is usually 1.25u, but can also be 1u.





