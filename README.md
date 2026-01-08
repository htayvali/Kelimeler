# Kelimeler

Kelime oyunları, dil uygulamaları ve kullanıcı girdisi doğrulama sistemleri için hazırlanmış,
temizlenmiş ve optimize edilmiş Türkçe ve İngilizce kelime listeleri ile
çok dilli sakıncalı kelime (blacklist) verilerini içerir.

---

## Word Lists for Games

This repository contains Turkish and English word lists prepared for word games,
puzzle games, and language-related applications.

The datasets are cleaned, deduplicated, and optimized for fast lookup in
HTML / JavaScript and mobile applications.

---

## 📦 Contents

### 🇹🇷 Turkish Word Lists
- Minimum length: **3 characters**, **4 characters**
- Single-column CSV
- UTF-8 encoded
- Plural, possessive, and case suffixes removed
- Approx. **125,000+** unique words

**Files:**
- `turkce_4plus_temizlenmis.csv`
- `turkce_3plus_temizlenmis_v2.csv`

---

### EN English Word List
- Minimum length: **3 characters**
- Alphabetic words only (`a–z`)
- Single-column CSV
- Lowercase
- Approx. **183,000+** unique words

**File:**
- `english_3plus_words.csv`

---

### 🚫 Multi-language Bad Words Blacklist
A curated blacklist of offensive or inappropriate words intended for
nickname validation and user-generated content filtering.

- Multi-language (e.g. `tr`, `en`, `nl`, `fr`, etc.)
- Two-column CSV with header
- Semicolon (`;`) separated
- UTF-8 encoded
- Deduplicated and normalized (lowercase)

**Format:**
```csv
word;lang
**File:** `yasak_kelime_github.csv`

⚙️ **Data Format Summary**

**Word Lists**
- One word per line
- No headers
- CSV-compatible
- Suitable for direct use with JavaScript `Set`, databases, or mobile applications

**Blacklist**
- Two columns: `word` and `lang`
- Header included
- Designed for fast lookup and filtering

🚀 **Typical Use Cases**
- Word search games
- Puzzle and anagram games
- Client-side word validation
- Nickname validation
- Leaderboards
- Language learning applications

📄 **Notes**
- Word lists are derived from open dictionary sources and processed using rule-based filtering
- The blacklist is intended **only for filtering purposes**
- Context is not evaluated; false positives are possible
- This dataset is intended for **educational and non-commercial use**

## License
This project is licensed under the MIT License.

