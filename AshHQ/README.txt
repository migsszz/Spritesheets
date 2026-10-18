Ash sheet for D5ModKit's Sheet picker, rebuilt at full quality from migsszz/Spritesheets/AshSpriteSheet01.png (1708x2963).
Every sprite pixel is copied exactly from the source: no scaling, smoothing or colour change.
Background: one flat colour, the sheet's light blue (147,187,236). Frames never touch; feet on a shared baseline per row.
strips/   same rows as separate PNGs.   rows.json   frame boxes per row.

Row -> picker animation (best guesses from pose shapes; confirm in the picker preview):
 stand (first idle frame) | wait 6+6 | walk 6+6 | dash 6+6 (+hand pieces) | squat 4+4 | attack_fist 4+4
 attack_sword 4+4 (+hands) | attack_lance 4+4 | attack_arrow 4+4 | attack_gun 4+4 | attack_ax 4+4 (+hands)
 one_arm_up 4+4 (+hands) | rolling 5+5 | damage 3+3 (+hands) | landing 5 front only
Left out: assembled strips, D2 idle strip, loose scarf pieces, palette swatches, credits.
