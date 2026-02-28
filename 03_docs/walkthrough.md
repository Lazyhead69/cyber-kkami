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
    - Mandatory Closing catchphrase: **"미션 완료! 기지개 펴고, 일상으로 고!"** (Mission complete! Stretch, and back to your routine, go!).
    - Added a mandatory 2-3 second digital jingle placeholder after the catchphrase.
    - **Physical Description Ban**: Prohibited the character from describing his own outfit/appearance in the narration, as the TTS represents his own voice and he is visually present.
