---
category: character
type: character
name: Character Sheet
summary: "A Paris-era Yellow King character sheet with ruled fields, investigative abilities, pushes, general abilities, and anchors."
tags:
  - pc
  - character
  - sheet
visibility: gm
approvalStatus: approved
knownToPlayers: false
keyLinks: []
aliases: []
lastEditedBy: Codex
cover: /wiki/media/REPLACE.jpg
---

<style>
.paris-sheet {
  max-width: 920px;
  margin: 0 auto 2rem;
  padding: 38px 52px 46px;
  color: #2d2725;
  background: #eee7dc;
  border: 18px solid #f8c8bd;
  outline: 1px solid #f5b2a3;
  outline-offset: -30px;
  font-family: Georgia, "Times New Roman", serif;
}
.paris-sheet * { box-sizing: border-box; }
.paris-title {
  margin: 0;
  color: rgba(244, 119, 98, .28);
  font-size: 72px;
  font-weight: 700;
  line-height: .95;
  text-align: center;
}
.paris-rule {
  margin: 14px 70px 22px;
  border-top: 3px double #f5b2a3;
}
.paris-sheet h2 {
  margin: 0 0 28px;
  text-align: center;
  font-size: 20px;
}
.paris-field {
  display: grid;
  grid-template-columns: 90px 1fr;
  gap: 12px;
  align-items: end;
  min-height: 34px;
  margin-bottom: 8px;
  padding: 0 12px 6px;
  background: rgba(255,255,255,.55);
  border-bottom: 2px solid #f5b2a3;
}
.paris-label,
.paris-section-title {
  font-weight: 700;
  font-variant: small-caps;
}
.paris-value {
  min-height: 24px;
}
.paris-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 28px;
  margin-top: 26px;
}
.paris-section-title {
  margin: 0 0 12px;
  font-size: 18px;
}
.paris-ruled,
.paris-small-box,
.paris-business {
  background: rgba(255,255,255,.55);
  background-image: repeating-linear-gradient(to bottom, transparent 0, transparent 31px, #f5b2a3 32px);
}
.paris-ruled {
  min-height: 166px;
  padding: 6px 10px;
  line-height: 32px;
}
.paris-small-box {
  min-height: 72px;
  margin-bottom: 20px;
  padding: 7px 10px;
  line-height: 32px;
}
.paris-small-box .paris-label,
.paris-business .paris-label {
  display: block;
  font-style: italic;
  font-weight: 400;
  font-variant: normal;
}
.paris-pushes {
  margin: 22px 0 30px;
  font-size: 18px;
  font-weight: 700;
}
.paris-circle {
  display: inline-block;
  width: 26px;
  height: 26px;
  margin-left: 8px;
  vertical-align: middle;
  border: 3px solid #f5b2a3;
  border-radius: 50%;
}
.paris-abilities {
  display: grid;
  gap: 8px;
}
.paris-ability {
  display: grid;
  grid-template-columns: 1fr 52px;
  gap: 12px;
  align-items: end;
  font-size: 20px;
}
.paris-rating {
  min-height: 24px;
  text-align: center;
  border-bottom: 2px solid #f5b2a3;
}
.paris-business {
  min-height: 430px;
  padding: 7px 10px;
  line-height: 32px;
}
@media (max-width: 760px) {
  .paris-sheet { padding: 30px 24px 34px; }
  .paris-title { font-size: 48px; }
  .paris-grid { grid-template-columns: 1fr; }
}
</style>

<div class="paris-sheet">
  <h1 class="paris-title">PARIS</h1>
  <div class="paris-rule"></div>
  <h2>CHARACTER SHEET</h2>

  <div class="paris-field"><span class="paris-label">Name</span><span class="paris-value"></span></div>
  <div class="paris-field"><span class="paris-label">Player</span><span class="paris-value"></span></div>
  <div class="paris-field"><span class="paris-label">Field</span><span class="paris-value"></span></div>
  <div class="paris-field"><span class="paris-label">Drive</span><span class="paris-value"></span></div>

  <div class="paris-grid">
    <section>
      <div class="paris-section-title">Investigative Abilities</div>
      <div class="paris-ruled">
        <br>
        <br>
        <br>
        <br>
      </div>

      <div class="paris-pushes">PUSHES (2): <span class="paris-circle"></span><span class="paris-circle"></span></div>

      <div class="paris-section-title">General Abilities</div>
      <div class="paris-abilities">
        <div class="paris-ability"><span>Athletics (Physical)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Composure (Presence)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Fighting (Physical)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>First Aid (Focus)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Health (Physical)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Mechanics (Focus)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Preparedness (Presence)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Riding (Physical)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Sense Trouble (Presence)</span><span class="paris-rating"></span></div>
        <div class="paris-ability"><span>Sneaking (Focus)</span><span class="paris-rating"></span></div>
      </div>
    </section>

    <section>
      <div class="paris-small-box"><span class="paris-label">I Rely On</span></div>
      <div class="paris-small-box"><span class="paris-label">I Seek To Protect</span></div>
      <div class="paris-business"><span class="paris-label">That Deuced Peculiar Business</span></div>
    </section>
  </div>
</div>

:::gm
## GM Notes

Secrets, flags, obligations, and the pressure points most likely to make this character choose badly.
:::
