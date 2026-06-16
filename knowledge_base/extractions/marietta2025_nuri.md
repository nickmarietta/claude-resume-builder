---
name: marietta2025_nuri
description: Nuri iOS app — skincare product browser with ingredient-based recommendation system; Nick owned full SwiftUI logic layer and Figma-to-code translation; ~15 screens; team of 4
metadata:
  type: project
---

# Nuri — iOS Skincare App

## Metadata
- **Project:** Nuri (repo: `jdc88/Nuri`)
- **Contributors:** **Nicklaus Marietta** + 3 teammates
- **Year:** ongoing (personal team project)
- **Type:** Personal team project (4 people)
- **Status:** Personal — no hackathon, no award
- **Correct framing:** "implemented app logic and connected Figma designs" — never claim design work (per config.md)

## Methods & Tools
- **Language/framework:** Swift, SwiftUI (iOS native)
- **Design handoff:** Figma (designed by teammates; Nick implemented from specs)
- **Database:** Open-source skincare product list with ingredient data (Nick connected SwiftUI views to database queries)
- **Recommendation system:** Ingredient-mapped recommendation logic surfacing products based on user skin tone, sensitivities, and preferences (Nick wired UI to recommendation outputs)
- **State management:** SwiftUI data binding, navigation, and state across ~15 screens

## Key Results
1. Implemented ~15 SwiftUI screens covering the full app walkthrough — all translated from teammate Figma designs into functional code
2. Connected UI to a working database of open-source skincare products with ingredient-level metadata
3. Wired SwiftUI views to an ingredient-mapped recommendation system that personalizes product results by skin tone and user-declared sensitivities
4. Handled data binding, navigation, and state management across the complete app flow
5. Served as the sole design-to-code bridge: teammates delivered Figma mocks, Nick made them functional in SwiftUI

## Novelty Claims
- Ingredient-level recommendation system personalized by skin tone and sensitivity inputs — not just keyword filtering
- Full design handoff workflow: Figma → SwiftUI with inferred interactions, transitions, and state (no Figma-to-Swift tooling used)

## Collaboration & Scope
- **Team of 4 — split:**
  - Nick: full SwiftUI logic layer, all Figma-to-code translation, database/recommendation UI integration
  - 3 teammates: Figma UI designs, database construction, recommendation system logic
- **Nick's sole ownership:** SwiftUI implementation (~15 screens), data binding, navigation, state management, connecting views to database and recommendation system outputs
- **Do NOT claim:** Figma designs, database schema/construction, recommendation algorithm logic — teammates built those

## Provenance Notes
- **Publication status:** N/A — personal project
- **Safe to claim:** SwiftUI implementation across ~15 screens; Figma-to-code translation; connecting UI to database queries and recommendation outputs; full app logic layer
- **Needs hedging:** The recommendation system and database exist — Nick connected to them, did not build them. Use "integrated" or "connected" not "built" or "designed" for those components.
- **Do NOT claim:** UI/UX design, database construction, recommendation algorithm

## Resume Bullet Seeds
1. Implemented ~15 SwiftUI screens from Figma designs for a skincare iOS app, handling data binding, navigation, and state management across the full app walkthrough
2. Integrated a SwiftUI product browser with an open-source ingredient database and a recommendation system that personalizes results by skin tone and user-declared sensitivities
3. Translated teammate Figma designs into functional SwiftUI code across the entire app, inferring interactions, transitions, and stateful behavior from static mocks
4. Wired SwiftUI views to backend database queries and recommendation outputs, enabling real-time product filtering and personalized ingredient-based suggestions
5. Contributed SwiftUI app logic for a 4-person team iOS project — sole engineer bridging Figma design handoff to working product code
