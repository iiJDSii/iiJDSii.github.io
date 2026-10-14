# Editorial image notes

The archive intentionally uses four different visual treatments: the existing safety architecture diagram, a portfolio robot photograph (`assets/images/caesar.jpg`), the VLM Tuner software screenshot (`assets/images/VLMT_project.jpg`), and a conceptual editorial illustration for the control essay. The technical diagrams remain inside the earlier essays where they explain the argument.

## Adversarial Robustness & AI Control

- Final asset: `assets/images/blog/blog_control-cover.png` (1536 × 1024). Copied into the repository from the generated output; the original was preserved.
- Method: built-in `image_gen` tool, new image, opaque background; no reference images, no CLI fallback.
- Status: AI-generated conceptual artwork. The transparent sphere and copper ring represent a control boundary; they are not real protective equipment. This is not documentary imagery of Ukraine or a deployed system. The article caption identifies that distinction.
- Final prompt:

> Use case: stylized-concept. Asset type: wide editorial cover for a serious engineering essay titled Adversarial Robustness & AI Control. Primary request: an original conceptual editorial illustration of autonomous systems under human control, visually distinct from flowcharts, dashboards, and stock robot-head images. Scene: a single small generic matte-charcoal quadcopter, hovering above an abstract desaturated terrain, enclosed by a large thin translucent blue glass sphere with a precise copper control ring around its equator; the sphere is an obvious visual metaphor for a boundary, not real equipment. One small calm human silhouette outside the sphere, upright at a simple control console, emphasizes scale and accountability. Style: sophisticated print editorial illustration combining soft 3D forms, fine paper grain, subtle engraved topographic texture, and restrained geometric composition. Palette: deep midnight blue, slate, warm ivory background, small burnt-copper accent; strong silhouette legible as a thumbnail. Landscape 3:2 framing, generous breathing room. No text, no letters, no logos, no flags, no charts, no arrows, no flowchart boxes, no weapons, no explosions, no people being targeted. This is conceptual artwork, not documentary footage of Ukraine or any real military deployment.
