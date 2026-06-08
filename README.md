<Project>
  <Layer name="Manga Panel">
    <Effect type="Shake" intensity="35"/>
    <Effect type="Zoom" scale="120"/>
  </Layer>

  <Layer name="Character">
    <Effect type="Flash" duration="0.1"/>
    <Effect type="MotionBlur" amount="50"/>
  </Layer>

  <Layer name="Text">
    <Animation type="FadeIn"/>
    <Animation type="ScaleUp"/>
  </Layer>

  <BeatSync bpm="140">
    <Transition type="Flash"/>
  </BeatSync>
</Project>
