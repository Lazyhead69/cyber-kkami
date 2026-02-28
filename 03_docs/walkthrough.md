# Walkthrough: Translation of Prompt Specialist Guidelines

## 1. Objective
Translate the existing Korean prompt engineering guidelines (`exemple.md`) into English to support international usage while maintaining all critical protocols and formatting rules.

## 2. Process
1.  **Read Source**: Accessed the contents of `/mnt/c/7.Github/cyber-kkami/exemple.md`.
2.  **Analyze Context**: Identified key sections including "Completeness Protocol", "Formatting Protocol", and "Character Profile".
3.  **Translation**: 
    *   Maintained technical terminology (e.g., "Style Wrapper", "Ambient Occlusion").
    *   Preserved strict formatting requirements for tags like `[English Image Prompt]`.
    *   Ensured the "Protocols" remained as forceful as in the original text (using terms like "Strictly forbidden", "Must adhere").
4.  **Verification**: Conducted a manual review of the translated text for accuracy and consistency.

## 3. Results
*   **Source File**: `exemple.md` (Korean)
*   **Target File**: `example.md` (English)
*   **Location**: `/mnt/c/7.Github/cyber-kkami/`

## 4. Optimization (Gemini Flash)
1.  **Objective**: Restructure the instructions into a hybrid XML/MD format to maximize instruction adherence and grounding for Gemini Flash models.
2.  **Implementation**: 
    *   Wrapped logical sections in semantically named XML tags.
    *   Used attributes to denote priority.
    *   Updated the `<character_profile>` to match **Kkami** (the black cat toddler) based on visual reference, ensuring the description is rich and non-abbreviated.
3.  **Result**: `optimized_example.md`

## 6. Style Update (2000s Animation Film)
- **Objective**: Adapt the "ambiance globale / DA" to match a nostalgic 2000s animated feature film.
- **Implementation**:
    - Replaced the "Watercolor/Lineart" style with a **"High-End 2000s 3D Animation (CGI/Pixar/Dreamworks)"** aesthetic.
    - Updated `DETECTED_STYLE` in `optimized_example.md` to specify 3D volume, squashing/stretching animation principles, and cinematic '2000s bloom' lighting.
    - Enhanced the `PROTAGONIST` profile to ensure Kkami is rendered with 3D fur shaders and glossy 3D eyes.
- **Verification**: The system instructions now explicitly guide the model to generate prompts with a consistent "Early-Digital Blockbuster" cinematic vibe.

## 7. Script Engine Optimization (v1)
- **Objective**: Translate and optimize the `kr_script_maker` prompt for creating deep narratives.
- **Implementation**:
    - Created `optimized_script_engine_v1.md` in English.
    - Integrated a **"Narrative Architect"** persona focused on Professor Kkami's YouTube channel.
    - Strictly enforced the **8,000+ character length** and **Pure TTS Output** (no tags) protocols.
    - Maintained consistency with the 2000s Animation style guide.

## 8. Standardized Introduction & Catchphrase
- **Objective**: Ensure Professor Kkami has a consistent and professional opening.
- **Implementation**:
    - Mandatory Catchphrase: **"모두 주목! 키보드 잡고, 고!"** (Everyone attention! Grab your keyboard, go!).
    - Mandatory Closing catchphrase: **"수고하셨어요! 머리 좀 식히고, 충전하러 고!"** (Great job! Cool your head, and go recharge!).
    - Added a mandatory 2-3 second digital jingle placeholder after the catchphrase.
    - **Physical Description Ban**: Prohibited the character from describing his own outfit/appearance in the narration, as the TTS represents his own voice and he is visually present.

## 9. TTS Optimization: No Digits Policy
- **Objective**: Improve the quality and naturalness of the Text-to-Speech (TTS) output.
- **Implementation**:
    - **No Digits Rule**: Prohibited the use of Arabic numerals (0-9). All numbers, dates, and years must be written out entirely in **Korean characters (Hangul)**.
    - This ensures the TTS engine reads numbers correctly according to the context (e.g., years vs. cardinal numbers).

## 10. Persona & Workflow Optimization (v2/v6)
- **Objective**: Propel the edutainment quality to blockbuster standards.
- **Implementation**:
    - **Script Engine (v2)**: 
        - **Dramatic Pacing**: 2,000-char segments with evolving emotional arcs (Curiosity -> Tension -> Climax -> Security).
        - **Visual Metaphor Glossary**: Standardized terminology (e.g., Firewall = Holographic Dome).
        - **Internal Director's Cues**: Silent metadata for scene intensity mapping.
    - **Visual Specialist (v6)**:
        - **Dynamic Framing**: 40/40/20 ratio for context, character, and overlays.
        - **Cinematic Angles**: High-status low-angles for Kkami; dutch/shaky cam for threats.
        - **Eye-Line Sync**: Professor Kkami now looks precisely at the digital elements being discussed.
- **Result**: Perfect synergy between narrative and visual generation.

## 11. Adult Audience Maturity Protocol (v3/v7)
- **Objective**: Maintain credibility and professionalism for adult, senior, and expert audiences.
- **Implementation**:
    - **Script Engine (v3)**: 
        - **Technical Anchoring**: Every visual metaphor must be linked to a real technical term (e.g., "The Firewall - this holographic dome").
        - **Tone Check**: Prohibited "fairy-tale" or childish language; replaced with high-stakes "Techno-Thriller" vocabulary.
    - **Visual Specialist (v7)**:
        - **Techno-Thriller Aesthetic**: Shifted from "magic/fantasy" to "architectural/digital" rendering.
        - **Refined Metaphors**: 
            - *Cloud* = Luminous Prism Data Center.
            - *Malware* = Systemic Parasite / Glitch-Sonde (sharp geometry, not cute).
- **Result**: A content generation engine that is both visually spectacular and intellectually serious.
