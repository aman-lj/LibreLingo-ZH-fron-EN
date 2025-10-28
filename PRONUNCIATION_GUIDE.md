# LibreLingo Mandarin Chinese Pronunciation Guide

## Overview
This guide explains the pronunciation features and learning approach used in this Mandarin Chinese course.

## Course Structure

### Modules
1. **Basics** (9 skills) - Foundation vocabulary and basic expressions
2. **Pronunciation & Tones** (4 skills) - Dedicated pronunciation and tone practice
3. **Intermediate** (5 skills) - Grammar, verbs, and more complex concepts

### Pronunciation Features

#### 1. Pinyin Support
All vocabulary includes:
- **Hanzi** (Chinese characters)
- **Pinyin** (Romanized pronunciation)
- **English translation**
- **Tone marks** (when applicable)

#### 2. Audio Support
- TTS enabled with Chinese voice (Zhiyu)
- Proper Chinese pronunciation playback
- Helps with tone recognition

#### 3. Tone Learning System

**Four Main Tones:**
- **1st tone (¯)**: High level - mā (mother)
- **2nd tone (´)**: Rising - má (hemp)
- **3rd tone (ˇ)**: Falling-rising - mǎ (horse)
- **4th tone (`)**: Falling - mà (scold)
- **Neutral**: No mark - ma (question particle)

**Tone Change Rules:**
- Two 3rd tones → 2nd + 3rd (e.g., 你好 nǐ hǎo → ní hǎo)
- 不 (bù) changes to bú before 4th tone
- 一 (yī) changes to yí before 4th tone

#### 4. Specialized Pronunciation Skills

**Pinyin Basics**
- Vowel sounds (a, o, e, i, u, ü)
- Initial consonants and finals
- Syllable structure

**Tones Practice**
- Individual tone practice
- Common tone change patterns
- Tone pairs and combinations

**Difficult Sounds**
- Retroflex consonants (zh, ch, sh, r)
- Aspirated vs unaspirated sounds
- Sounds challenging for English speakers

**Tone Pairs**
- Common two-character words
- Natural tone combinations
- Real-world pronunciation patterns

## Learning Recommendations

### For Beginners
1. Start with **Basics** module for essential vocabulary
2. Practice pronunciation with **Pronunciation & Tones** module
3. Use audio playback to hear correct pronunciation
4. Focus on tone accuracy from the beginning

### Pronunciation Practice Tips
1. **Listen first**: Use audio playback extensively
2. **Practice tones**: Master individual tones before combinations
3. **Record yourself**: Compare with native pronunciation
4. **Minimal pairs**: Practice similar-sounding words
5. **Tone drills**: Practice tone change rules

### Common Challenges
- **Retroflex sounds** (zh, ch, sh, r): curl tongue back
- **Aspiration** (p, t, k vs b, d, g): feel the puff of air
- **Tone memory**: associate tones with hand gestures or colors
- **Tone changes**: learn the rules and practice common patterns

## Technical Implementation

### YAML Structure
Each skill follows LibreLingo's YAML format with added pronunciation fields:
- `Pronunciation`: Pinyin with tone marks
- `Tone`: Tone description (for pronunciation skills)
- `Pinyin`: Phonetic components (for pinyin skills)

### Audio Configuration
```yaml
Settings:
  Audio:
    Enabled: True
    TTS:
      - Provider: Polly
        Voice: Zhiyu  # Chinese voice
        Engine: standard
```

## Future Enhancements

Potential additions for improved pronunciation learning:
1. **Tone visualization** - graphical tone contours
2. **Recording comparison** - user voice vs native speaker
3. **Interactive tone drills** - gamified tone practice
4. **Minimal pair exercises** - distinguishing similar sounds
5. **Speed adjustment** - slower pronunciation for learning

## Resources

For additional pronunciation practice:
- Pinyin charts and audio reference
- Tone pair frequency lists
- Common pronunciation errors and corrections
- Native speaker audio examples