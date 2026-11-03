# Far Horizon browser playback check

Open **FAR_HORIZON_BROWSER_PLAYBACK_CHECK.pptx** in the same PowerPoint browser app you use for the storybook. Choose **Slide Show → From Beginning** (or **Present**). Editing view shows a still image and does not test autoplay.

On each of the three slides, wait five seconds without clicking the picture. Look at the **VIDEO TIME** counter near the bottom left. If the number changes, the media is playing. Advance with Right Arrow.

1. Current video timing.
2. Alternative automatic Play timing.
3. Animated-image control. This diagnostic is shorter and lower resolution; it tests image playback independently of video playback.

Report which slide numbers start moving automatically, whether the counter keeps moving after 12 seconds on slides 1–2, and which browser you used. That result will identify whether a timing change or a different playback format is needed for this browser.

The full revision 5 storybook is unchanged. Its movies are embedded and valid, and its background timings specify automatic start and indefinite looping. This diagnostic passed ZIP, relationship, native timing-target and video-decoding checks. The animated-image control contains 48 frames and an infinite-loop flag. Actual PowerPoint browser playback must be checked in your browser session.
