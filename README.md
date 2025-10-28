# LibreLingo-ZH-from-EN

Mandarin course for English speakers with comprehensive pronunciation support

## Overview

This is a LibreLingo-based Mandarin Chinese course designed for English speakers, featuring:

- **18 skills** across 3 learning modules
- **500+ vocabulary words** with pronunciation guides
- **Audio support** with Chinese TTS voice
- **Comprehensive tone learning** system
- **Pinyin-based pronunciation** guides

## Course Structure

### 🎯 Basics Module (9 skills)
Foundation vocabulary for everyday communication:
1. **Greetings** - Basic expressions and politeness
2. **Numbers** - Counting and numbers 0-10,000
3. **Family** - Family members and relationships
4. **Food & Drinks** - Common food items and beverages
5. **Pronunciation Basics** - Essential tone practice
6. **Common Phrases** - Everyday expressions
7. **Time & Date** - Days, months, time expressions
8. **Travel** - Transportation and travel vocabulary
9. **Shopping** - Commerce and shopping terms

### 🔊 Pronunciation & Tones Module (4 skills)
Specialized pronunciation and tone practice:
1. **Pinyin Basics** - Vowels, consonants, syllable structure
2. **Tones Practice** - Four tones and tone changes
3. **Difficult Sounds** - Retroflex consonants and challenging sounds
4. **Tone Pairs** - Common tone combinations in words

### 📚 Intermediate Module (5 skills)
Grammar and more complex concepts:
1. **Basic Grammar** - Particles and sentence structure
2. **Common Verbs** - Action verbs and modal verbs
3. **Adjectives** - Descriptive words
4. **Questions** - Question words and patterns
5. **Directions** - Location and directions

## Pronunciation Features

### 🎵 Tone Learning System
- **4 main tones** + neutral tone
- **Tone change rules** (e.g., two 3rd tones → 2nd + 3rd)
- **Audio playback** with Chinese TTS voice (Zhiyu)
- **Visual tone marks** in all vocabulary

### 🔤 Pinyin Support
Every word includes:
- Chinese characters (Hanzi)
- Pinyin with tone marks
- English translation
- Audio pronunciation

### 🎧 Audio Configuration
```yaml
Settings:
  Audio:
    Enabled: True
    TTS:
      - Provider: Polly
        Voice: Zhiyu
        Engine: standard
```

## Key Features

### ✅ What Makes This Course Effective
- **Gradual progression** from basics to intermediate
- **Dedicated pronunciation module** for tone mastery
- **Real-world vocabulary** for practical use
- **Audio support** for listening practice
- **Tone-aware learning** from the very beginning

### 🎯 Learning Focus
- **Conversational Chinese** for everyday situations
- **Proper pronunciation** and tone accuracy
- **Essential grammar** patterns
- **Cultural context** through vocabulary choices

## Technical Details

### File Structure
```
course/
├── course.yaml              # Main course configuration
├── basics/
│   ├── module.yaml          # Basics module config
│   └── skills/              # 9 basic skill files
├── pronunciation/
│   ├── module.yaml          # Pronunciation module config
│   └── skills/              # 4 pronunciation skill files
└── intermediate/
    ├── module.yaml          # Intermediate module config
    └── skills/              # 5 intermediate skill files
```

### YAML Format
Each skill follows LibreLingo's standard format with enhanced pronunciation support:
- `Word`: Chinese characters
- `Translation`: English meaning
- `Pronunciation`: Pinyin with tone marks
- Additional fields for pronunciation skills (tone descriptions, etc.)

## Getting Started

1. **Beginners**: Start with the Basics module
2. **Pronunciation focus**: Practice with the Pronunciation module alongside Basics
3. **Intermediate learners**: Move to Intermediate module after mastering basics

## Pronunciation Guide

See [PRONUNCIATION_GUIDE.md](./PRONUNCIATION_GUIDE.md) for detailed information on:
- Tone system explanation
- Pronunciation practice tips
- Common challenges and solutions
- Technical implementation details

## License

This course is licensed under Attribution-ShareAlike 4.0 International (CC BY-SA 4.0).

## Repository

Based on LibreLingo framework. Repository configuration available in course.yaml.
