# Prototype plan

## Phase 1 — imaging feasibility

Test focus, framing, glare, and colour consistency with a Raspberry Pi and camera. Use ordinary nonclinical test images first. Document image-quality failure cases and decide whether different optics are needed.

## Phase 2 — clinical target and data

Choose one narrowly defined target with clinical advice. Secure permission and consent for data. Include noninfectious lookalikes. Do not label every red eye as an infection.

## Phase 3 — model development

Train a lightweight CNN on a development machine. Use patient-separated train/validation/test splits and an independent test set. Evaluate clinically meaningful sensitivity, specificity, uncertainty, and subgroup performance. Investigate Transformer models only if there is a justified need.

## Phase 4 — Raspberry Pi integration

Implement capture, quality checks, preprocessing, model inference, and a result screen. Benchmark CPU inference first. Select an accelerator only if runtime measurements and model compatibility support it.

## Phase 5 — validation and iteration

Validate the complete intended workflow and image capture conditions with appropriate clinical oversight. Define handling for unreadable images and uncertain outputs. Assess eye safety of any illumination and the privacy of stored images.

## Honest presentation

Use labels such as “Concept”, “Simulated result”, and “Research prototype”. Do not claim measured accuracy, a completed device, confirmed infection detection, disease prevention, or regulatory clearance without evidence.
