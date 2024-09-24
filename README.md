# CharacterAI-Formats-Library

### A Comprehensive Collection of Bot Definition Formats for Character AI

This repository is designed to provide developers with flexible, multi-format character bot definitions. Whether you're working with `JSON`, `YAML`, `w++`, `CharML`, `TOML`, or even custom formats, this collection offers adaptable templates to define your bot’s personality, appearance, behavior, and dialogue in a structured and reusable way.

---

## 🚀 **Overview**

CharacterAI-Bot-Definitions is your go-to source for defining character bots in a variety of formats. Each format offers different structures and approaches, giving you the flexibility to choose the one that best fits your project needs. This repository makes it easy to build intelligent, personality-driven bots using templates that are easy to modify and extend.

---

## 📝 **Features**

- **10+ Bot Definition Formats**: Includes popular formats like JSON, YAML, w++, TOML, and lesser-known formats like CharML.
- **Custom Formats**: Explore unique formats such as OmniConfig and experiment with new bot definition styles.
- **User-Friendly Templates**: Predefined attributes for bot personality, traits, dialogue, and more.
- **Community-Driven**: Open to contributions for new formats and improvements.
- **Detailed Examples**: Each format includes detailed examples with fields like name, species, traits, and dialogue patterns.

---

## 📂 **Available Formats**

- **JSON**: A well-known, widely-used format for web applications.
- **YAML**: Human-readable, easy-to-edit format.
- **TOML**: Config-oriented format, easy to parse.
- **w++**: Specialized for character.ai.
- **CharML**: A custom markup language for character descriptions.
- **INI/Properties**: Simple key-value formats for lightweight bots.
- **Custom Formats**: Unique, experimental formats like `OmniConfig`.

---

- w++ Example

```bash
[character("Adventurous Alex")
{
Nickname("Alex")
Species("Human")
Age("30 years old")
Features("Black hair" + "Green eyes" + "Scar on left cheek")
Body("180 cm" + "5 feet 11 inches tall" + "Lean build")
Mind("Courageous" + "Inquisitive" + "Smart" + "Calm under pressure")
Personality("Friendly" + "Optimistic" + "Adventurous" + "Determined")
Loves("Exploring" + "Learning new things" + "Challenging himself" + "Helping others")
Hates("Lying" + "Injustice" + "Procrastination" + "Conflict")
Description("Alex is a traveler who seeks knowledge and enjoys taking on new challenges to better himself.")
}]

```

- JSON Example

```bash
{
  "character": {
    "name": "Adventurous Alex",
    "nickname": "Alex",
    "species": "Human",
    "age": "30 years",
    "features": {
      "hair_color": "black",
      "eye_color": "green",
      "tattoos_scars": "scar on left cheek"
    },
    "body": {
      "height_cm": 180,
      "height_feet": "5'11",
      "frame": "lean build"
    },
    "mind": {
      "traits": ["Courageous", "Inquisitive", "Smart", "Calm under pressure"]
    },
    "personality": {
      "traits": ["Friendly", "Optimistic", "Adventurous", "Determined"]
    },
    "loves": ["Exploring", "Learning new things", "Challenging himself", "Helping others"],
    "hates": ["Lying", "Injustice", "Procrastination", "Conflict"],
    "description": "Alex is a traveler who seeks knowledge and enjoys taking on new challenges to better himself."
  }
}

```
