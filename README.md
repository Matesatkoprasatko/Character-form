# Anime Character Creator

A comprehensive web-based form designed for building detailed anime character profiles. This interface allows creators to define everything from core identity and archetypes to specific power levels and backstories.

## Features

- **Core Identity:** Fields for name, alias, secret identity, and hometown.
- **World Origin:** A selection menu to categorize the character's origin.
- **Archetype Selection:** Radio buttons to define the character's role (e.g., Shonen Hero, Rival, Sensei).
- **Stats & Abilities:** - Power Level selection (G-Rank and above).
    - Numerical age input and date of "awakening".
    - Multi-select checkboxes for unique abilities like Super Strength, Flight, or Time Travel.
- **Media & Contact:** Supports portrait uploads, external image URLs, and creator contact information.
- **Backstory:** A dedicated text area for the character's lore and "Nindo" (ninja way).

## Form Components

### Input Types Used
- `text`: For names and identities.
- `number`: For age tracking.
- `date`: For chronological events.
- `radio`: For mutually exclusive archetypes.
- `checkbox`: For multiple ability selections.
- `file`: For character portrait uploads.
- `url`: For referencing external artwork.
- `textarea`: For long-form storytelling.

## Design

The form is structured using logical `fieldset` groups and `legend` tags to ensure a clear hierarchy and improved accessibility. It uses the **Nunito** font family for a modern, clean aesthetic suitable for creative applications.

## Technical Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari).
- `style.css` file linked for layout and responsiveness.
- Google Fonts connection for typography.

## Usage

1. Fill out the "Core Identity" section.
2. Select one character "Archetype".
3. Define the character's "Stats & Abilities".
4. Provide a portrait or reference link and write the backstory.
5. Click **Finalize Character** to process the data.
