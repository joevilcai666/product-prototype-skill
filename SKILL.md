---
name: product-prototype
description: Create and iterate on interactive, high-fidelity web prototypes of software products, including mobile, desktop, and web app concepts. Use when a user wants to experience or compare product designs before implementation.
---

# Interactive product prototypes

Turn a product idea into a polished, runnable web prototype that people can experience and review. Adapt the experience to the intended platform: a phone app should feel plausible on a phone, a desktop application should use an appropriate desktop workspace, and a web app should suit its intended screens. A browser cannot reproduce every native or backend capability; make limitations clear.

## Understand and decide

Read the user's brief and any relevant existing product decisions, design references, and project instructions. Preserve explicit constraints and previously approved decisions. Separate known requirements from assumptions. If a missing decision would materially change the product direction or core journey, ask concise questions with concrete options and a recommendation. Otherwise make reasonable assumptions and proceed; do not ask the user to choose fonts, colors, libraries, or routine tools. A clear brief needs no discovery interview.

Identify the target user, their goal, the key journey, and the intended device. For a broad idea, choose a representative end-to-end journey that expresses the core value. Honor a more specific requested scope. Use plausible, consistent content and data; avoid filler and unexplained invented capabilities.

## Explore three directions

By default build at least three distinct, high-fidelity directions for the first review, even if the user did not ask for alternatives. All must support the same core user goal and journey so that they can be compared. Differ meaningfully in visual language, layout, information hierarchy, or interaction model; color swaps alone are not directions. If exploring materially different product strategies, identify that difference and preserve a comparable task. Respect explicit user instructions that change the number or scope.

Before building, identify the specific differences in page structure, navigation, information hierarchy, or interaction for each direction. Compare the rendered directions after building: if two have essentially the same layout and differ mainly in color, type, or decoration, redesign one before delivery. Differences should remain visible along the core journey, not only on the opening screen.

Give each direction a concise name and a clear rationale. Study high-quality examples relevant to the product category and target platform when useful, and identify what makes their hierarchy, density, interactions, and visual details effective. Choose a visual language appropriate to this product rather than a fixed house style. Define a coherent palette, type scale, spacing, icon treatment, and component language for each direction. Use suitable, licensed visual assets or available image-generation tools when they improve the result; do not copy another product's distinctive design. Avoid boilerplate cards, generic decorative headings, filler labels, repetitive subtitles, dead controls, and arbitrary ornament. Content should help people understand, decide, or act.

Make interaction feel deliberate: give controls immediate, subtle feedback; use motion only when it clarifies a change or spatial relationship; keep frequent actions fast and honor reduced-motion preferences. Make transitions interruptible where practical. Keep controls and gestures usable with keyboard and touch.

Present one direction at a time at a realistic, consistent viewport size. For phone or desktop app concepts, place the product in a convincing, appropriately proportioned device or window frame on larger screens. Use the surrounding review area for direction switching and concise descriptions, separate from the product itself. The product viewport should scroll independently, with navigation and overlays constrained to it. At narrow screen sizes, adapt or remove the frame and secondary review copy rather than shrinking or obscuring the app. For browser-native web products, use an appropriate browser viewport rather than forcing a phone frame. Switching directions should be immediate, clearly indicate the active choice, support keyboard use, and preserve shared demo data and context where feasible.

For desktop apps, design for a real working session: prioritize the user's current work, use the available width for a coherent workspace and contextual detail when useful, and keep navigation and actions legible. Avoid treating a desktop window as a stretched phone screen or a stack of generic summary cards. Check the preview in both a wide browser window and a narrower review panel; collapse secondary review chrome or adapt the layout without clipping navigation or scaling text down. Offer a way to view the full desktop layout when the available width cannot show it comfortably.

Each direction must be runnable and support the core journey with meaningful state changes, navigation, feedback, and relevant empty, error, and recovery states. Make data consistent across screens. Use local state or fixtures for unconnected services. Identify simulated results and do not represent them as real analysis, payments, notifications, accounts, or other external actions.

## Build and inspect

Use the existing project's conventions when appropriate; otherwise select a simple stack that can run locally. Keep exploratory work isolated from production behavior. Inspect available browser, design, and image tools; use equivalent capabilities in the current environment. If needed, find free public or open-source resources and install ordinary project-local dependencies. Avoid requiring the user to configure services for a prototype. Do not perform account registration, incur charges, or publish without authorization. Follow applicable project instructions and asset licenses.

Run the prototype. Open every direction in a browser or equivalent visual tool, inspect screenshots at the intended device size, and actually exercise the core journey and relevant states. Critique the rendered result, not just the source: check first-screen hierarchy, density and whitespace, typography, icon consistency, image quality, alignment, contrast, content, navigation, interaction feedback, and clipping. Compare directions for meaningful visual and structural differences, and inspect both the device frame and narrow-screen adaptation. Fix material defects, capture new evidence, and inspect again. A functional pass alone does not establish visual quality. Use a suitable fallback if a tool is unavailable; clearly report what could not be visually or functionally checked. Do not claim full native fidelity or verification that did not occur.

Deliver a local preview and the source path, explain how to open it, and briefly describe the differences between directions, assumptions, simulated capabilities, and any verification limits. Do not deploy publicly unless requested. Preserve the directions for comparison.

## Iterate

After review, develop the selected direction. The user can combine specific elements from multiple directions; integrate them into a coherent design instead of simply splicing incompatible parts together. Preserve approved visual and interaction decisions, expand the requested journeys and states, and repeat visual and functional checks. An approved prototype is a design reference, not evidence that the production application or its services are implemented.
