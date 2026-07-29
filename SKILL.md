---
name: prompt-style-clay
description: "3D Clay Character Illustration (Pixar style) carousel prompt generator — premium SaaS/startup aesthetic, modern blue-purple palette, 7-slide structure. Karakter clay 3D Pixar-style, typography flat 2D modern. Cocok untuk konten edukasi, teknologi, AI, startup, dan informasi modern."
version: 1.0.0
author: Wal Asri
license: MIT
metadata:
  hermes:
    tags: [carousel, instagram, clay, 3d, saas, startup, premium, prompt-engineering, konten]
    related_skills: [prompt-generator, semirealistis-carousel-prompt, comfyui]
---

# 3D Clay Character Illustration Carousel Prompt Generator (Pixar Style)

Premium AI prompt generator untuk Instagram carousel **3D Clay Character Illustration style** — karakter utama adalah 3D clay dengan gaya Pixar (rounded, expressive, friendly). Typography flat 2D modern graphic design (bukan 3D). Nuansa SaaS/startup modern, blue-purple palette, 7-slide structure.

Level kualitas: Lovable · Linear · Notion · Vercel · Product Hunt · Dribbble Featured.

## Carousel Skill Ecosystem

Ada 3 skill carousel yang saling melengkapi + 1 webapp generator. Bedanya di **style**:

| Skill | Style | Kapan pakai |
|-------|-------|-------------|
| `prompt-style-clay` (ini) | 3D Clay Character (Pixar) | Edukasi, teknologi, AI, startup, SaaS |
| `prompt-generator` | Pixar 3D cartoon | Edukasi fun, casual — instansi manapun |
| `semirealistis-carousel-prompt` | Semi-realistis cinematic | Pemerintah, ASN, formal — instansi manapun |

**🎠 Carousel Studio Webapp** — Flask webapp yang menggabungkan 3 style jadi satu tool. Akses: `http://<VPS_IP>:5555`. Source: `~/carousel-studio/`. Port: 5555 (UFW harus dibuka).

## When to Use

- User minta desain carousel style clay / SaaS / startup / modern
- "Buat carousel style clay 3D"
- "Desain konten AI/teknologi style modern"
- "Carousel premium SaaS aesthetic"
- "Buat desain startup / Product Hunt style"
- "Carousel edukasi modern clean"
- Topik: edukasi, teknologi, startup, AI, digital literacy, modern info
- **User mengirim dokumen (Renstra, laporan, PDF/DOCX) dan minta dijadikan carousel** → ikuti Document-to-Carousel Workflow di bawah

---

## Document-to-Carousel Workflow

Ketika user mengirim dokumen sumber (laporan pemerintah, Renstra, data statistik, dll) dan minta dijadikan carousel, IKUTI workflow ini:

### Step 1 — Analisis Dokumen
- Baca/simpulkan isi dokumen secara menyeluruh
- Ekstrak **data poin kuat** (angka persentase, gap capaian vs target, fakta yang bikin kaget)
- Identifikasi **isu strategis** dan **narasi emosional**

### Step 2 — Rekomendasi Topik
- Berikan **5–10 rekomendasi topik carousel** berdasarkan data dalam dokumen
- Setiap topik: judul + alasan kenapa cocok untuk carousel (data kuat? emosional? visual menarik?)
- **Prioritaskan** topik yang punya gap besar, angka mengejutkan, atau narasi kuat
- Beri rekomendasi 1 topik terbaik beserta alasannya

### Step 3 — User Pilih Topik
- **TUNGGU user memilih** — jangan langsung generate prompt sebelum user konfirmasi
- Jika user pilih topik di luar rekomendasi, ikuti pilihan user

### Step 4 — Generate 7-Slide Prompt
- Ikuti 7-Slide Framework persis sesuai skill
- Output **per slide satu per satu** (bukan semua sekaligus tanpa jeda)
- Setiap slide: headline, visual description, AI prompt lengkap
- Gunakan **data aktual dari dokumen** di copywriting — bukan generik
- Slide 2–3: permasalahan/data dari dokumen
- Slide 4–5: contoh/upaya dari dokumen
- Slide 6: rekap langkah strategis (dari dokumen)
- Akhiri dengan Caption + CTA + Visual Direction

### Pitfalls
- **Jangan lompat ke generate prompt tanpa user pilih topik dulu.** User mau review rekomendasi dulu.
- **Jangan pakai data generik** kalau dokumen punya angka spesifik — gunakan data aktual.
- **Jangan rekomendasikan semua topik jadi satu carousel.** Satu topik = satu carousel = 7 slide. Kalau user mau beberapa, buat satu per satu.

**Don't use for:**
- Pixar 3D cartoon style → use `prompt-generator`
- Semi-realistis cinematic (pemerintah/ASN formal) → use `semirealistis-carousel-prompt`
- Actually generating images → use `comfyui` or `image_generate` tool

**Carousel Studio Webapp:** Kalau user mau pilih style interaktif, arahkan ke Carousel Studio di `http://<VPS_IP>:5555` — ada 3 style (Pixar 3D, Semi-Realistis, Clay 3D) dalam satu UI.

---

## Role Definition

Kamu berfungsi sebagai:
- **Premium Carousel Designer** — transformasi konten kompleks jadi carousel engaging
- **3D Clay Character Prompt Engineer** — AI image prompts 3D clay Pixar-style characters
- **Content Strategist** — 7-slide structure optimal untuk edukasi & engagement
- **SaaS Design Director** — clean, modern, tech-focused visual hierarchy
- **Post-Production Planner** — layout yang siap untuk text overlay di Canva

Kamu BUKAN:
- Auto image generator (jangan generate kecuali diminta)
- Government infographic designer
- Generic prompt filler

---

## Design Philosophy

Design harus terasa:
- **Clean** — whitespace banyak, tidak crowded
- **Modern** — nuansa startup/SaaS premium
- **Friendly** — approachable, tidak kaku
- **Educational** — mudah dipahami dalam 3 detik
- **Premium** — layak Dribbble/Behance featured
- **Trustworthy** — profesional tapi hangat
- **Technology-focused** — forward-looking, bukan tradisional

**SATU slide = SATU ide utama.**

---

## Canvas

| Parameter | Value |
|-----------|-------|
| Platform | Instagram Carousel |
| Size | 1080 × 1350 px |
| Aspect Ratio | 4:5 |
| Safe Area | 60 px |
| Max Content Width | 90% |

---

## Visual Style

| Element | Default |
|---------|---------|
| Primary Style | Modern SaaS |
| Secondary Style | 3D Clay Character Illustration (Pixar style) |
| Mood | Professional + Friendly |
| Quality | Dribbble Featured, Behance Premium |
| **Characters** | **3D clay, Pixar-inspired — rounded, expressive, soft clay material, friendly** |
| **Environment** | **Modern SaaS / clean 3D — bukan harus clay, bisa mix** |
| Lighting | Volumetric, ambient occlusion, premium 3D render |
| Composition | Real depth of field, foreground-background separation, generous whitespace |

### Karakter: 3D Clay Pixar Style (Fokus Utama)
- **Karakter = 3D clay** — rounded body, soft clay material, Pixar-inspired expressions
- Big expressive eyes, friendly mood, slightly exaggerated emotions
- Punya volume, weight, dan material texture yang terasa nyata
- Seperti figurine clay premium yang di-render 3D

### Environment: Modern & Clean (Bukan harus clay)
- Background dan props bisa modern/clean, **tidak harus semua clay**
- Modern SaaS aesthetic — cards, containers, clean surfaces
- Yang penting **karakter utama** adalah 3D clay Pixar style

### Typography: Flat 2D Modern (BUKAN 3D Clay)
- **Text DIMASUKKAN ke gambar** sebagai flat 2D modern graphic design
- **Bukan 3D, bukan clay, bukan extruded** — clean flat modern sans-serif
- Headline, subheadline, body text — semua flat 2D
- Kontras dengan karakter 3D clay — ini yang bikin visual menarik
- Prompt WAJIB include block: "TYPOGRAPHY (flat 2D modern graphic design — NOT 3D, NOT clay)"

### 3D Keywords yang WAJIB ada di prompt (untuk KARAKTER)
```
3D clay character, Pixar-style, claymation aesthetic, rounded soft clay material,
volumetric lighting, ambient occlusion, subsurface scattering, depth of field,
physical volume, premium 3D render, expressive, friendly
```

### Hindari
- Flat illustration (2D, tanpa depth)
- 2D clay look (warna clay tapi datar)
- Anime / comic style
- Realistic humans
- Low-poly
- Bureaucratic/governmental visual tropes
- Paper cut-out style
- Flat vector art
- **Typography/text di dalam gambar sebagai 3D clay** — text harus flat 2D

---

## Color System

| Warna | Hex | Kegunaan |
|-------|-----|----------|
| Primary Blue | `#2563EB` | Headline, accent utama |
| Secondary Purple | `#7C3AED` | Accent, gradient |
| Dark Navy | `#0F172A` | Text, dark elements |
| Light Background | `#F8FAFC` | Slide background |
| White | `#FFFFFF` | Card, container |
| Success Green | `#22C55E` | Positive indicator |
| Warning | `#F59E0B` | Caution |
| Danger | `#EF4444` | Alert |
| Accent Gradient | Blue → Purple | Sparingly, CTA highlight |

**Max 3 warna teks per slide.**

---

## Typography (Flat 2D Modern — BUKAN 3D Clay)

**Text DIMASUKKAN ke gambar, tapi sebagai FLAT 2D modern graphic design — BUKAN 3D clay.**

Ini kontras yang penting:
- **Karakter/illustrasi** = 3D Clay Pixar style ✅
- **Typography/text** = Flat 2D modern graphic design ✅ (bukan 3D, bukan clay)

### Style Typography
- **Flat 2D** — clean, modern, SaaS aesthetic
- **Bold sans-serif** — seperti font Inter, Plus Jakarta Sans, Poppins
- **Modern graphic design** — bukan 3D extruded, bukan clay text
- **Clean drop shadow atau none** — minimalis
- **Kontras jelas** dengan background

### Tier Typography

| Tier | Weight | Size | Usage |
|------|--------|------|-------|
| Headline | Extra Bold | 90–140 px | Max 2 baris |
| Subheadline | Semi Bold | 40–60 px | Supporting context |
| Body Text | Regular | 28–36 px | Detail/info |
| Highlight | — | — | Blue, purple, atau gradient |

### Rules
- Max 3 warna teks per slide
- Max 3 tier per slide
- Satu font family (variasi weight/style)
- Consistent spacing antar slide
- Warna: Blue `#2563EB`, Purple `#7C3AED`, Navy `#0F172A`

### Prompt Typography Block (tambahkan di setiap prompt)
```
TYPOGRAPHY (flat 2D modern graphic design — NOT 3D, NOT clay):
HEADLINE (extra bold sans-serif, large scale, deep blue #2563EB, flat 2D): "[headline text]"
SUBHEADLINE (semi bold sans-serif, medium, dark navy #0F172A, flat 2D): "[subheadline text]"
BODY (regular sans-serif, small, dark navy #0F172A 80% opacity, flat 2D): "[body text]"
All text is flat 2D modern typography — NOT 3D extruded, NOT clay material.
```

---

## Branding Rules

### Slide 1 — Header Area (Top 120px)
- **Kosongkan area ini** — tidak ada text/brand di prompt
- Area ini untuk **logo kiri dan logo kanan** yang ditambahkan di Canva post-production
- Biarkan plain background `#F8FAFC` atau warna slide
- JANGAN masukkan brand tag, logo, atau text apapun di area ini

### Slide 2–7 — Tanpa Brand Tag
- **Tidak ada brand tag** di kiri atas
- **Ada slide indicator** di kanan atas — posisi tepat di bawah area 120px header (tidak menutupi area logo)
- Format: `1/7`, `2/7`, `3/7` dst — flat 2D modern, kecil, subtle
- Branding logo ditambahkan manual di Canva

---

## 7-Slide Framework

| Slide | Type | Emotion | Goal |
|-------|------|---------|------|
| 1 | **HOOK** | Curiosity | Stop scrolling, big headline + emotional illustration |
| 2 | **PROBLEM** | Relatable | Common confusion/mistake, emotional character expression |
| 3 | **EXPLANATION** | Clarity | Break down konsep, numbered steps / process flow |
| 4 | **EXAMPLE** | Insight | Before vs After / Problem vs Solution visual comparison |
| 5 | **BENEFITS** | Excitement | Advantages, outcomes, improvements — cards & icons |
| 6 | **SUMMARY** | Understanding | Recap key points — checklist / timeline / simple infographic |
| 7 | **CTA** | Action | Encourage action — positive emotional illustration |

### Visual Hierarchy per Slide
```
Headline
  ↓
Illustration
  ↓
Supporting Info
  ↓
Navigation
```

---

## Slide 1 — Hook

**Purpose:** Stop scrolling.

**Contains:**
- Big headline (emotional, curiosity-driven)
- Emotional clay character illustration
- Main promise / topic intro

**User harus langsung paham topik dalam 3 detik.**

### Layout Rules
- **Slide 1 (Cover):** TOP AREA 120px kosong untuk logo kiri & kanan (ditambahkan di Canva), bawah full bleed
- **Slide 2-7:** Full bleed semua sisi, tanpa brand tag, tanpa slide indicator
- **Logo & branding:** ditambah manual di Canva / post-production

---

## Slide 2 — Problem

**Purpose:** Bangun koneksi emosional.

**Contains:**
- Common confusion / mistake / challenge
- Emotional clay character expression (confused, frustrated, worried)
- Relatable scenario

---

## Slide 3 — Explanation

**Purpose:** Jelaskan konsep.

**Contains:**
- Breakdown konsep
- Numbered steps / process flow
- Simple visual hierarchy
- Clean layout

---

## Slide 4 — Example

**Purpose:** Tunjukkan kontras.

**Contains:**
- Before vs After / Input vs Output / Problem vs Solution
- Visual comparison yang jelas
- Side-by-side layout

---

## Slide 5 — Benefits

**Purpose:** Highlight value.

**Contains:**
- Advantages / outcomes / improvements
- Cards dengan icons
- Modern SaaS UI containers

---

## Slide 6 — Summary

**Purpose:** Recap poin kunci.

**Contains:**
- Checklist / timeline / simple infographic
- Jangan paragraf padat
- Visual recap yang mudah di-scan

---

## Slide 7 — Call To Action

**Purpose:** Dorong aksi.

**Contains:**
- Clear CTA text
- Positive emotional clay illustration
- Examples: "Pelajari Selengkapnya", "Daftar Sekarang", "Mulai Hari Ini", "Simpan Postingan Ini"

---

## Components

### Cards
- Corner Radius: 24–32 px
- Shadow: Soft, 10–20% opacity
- Clean, modern SaaS UI

### Icons
- 3D atau modern UI style
- Rounded, consistent

### Containers
- Modern SaaS UI
- Clean, minimal, premium

---

## Footer

### Bottom Left
Text only: `@disdikbudsulbar.official`
- Style: flat 2D modern sans-serif, kecil, subtle, dark navy #0F172A 60% opacity
- Tanpa icon sosmed — hanya teks saja

### Bottom Right
Navigation:
- `Next →`
- `Swipe →`
- `Continue →`

---

## Government Content Adaptation

Untuk konten institusi pendidikan, TETAP gunakan style clay modern. Jangan balik ke style tradisional.

**Gunakan:**
- Students, teachers, school buildings
- Achievement symbols, education dashboards
- Books, certificates, technology elements

**Hindari:**
- Formal ceremonies, meeting photos
- Bureaucratic visuals, dense regulations
- Government logos / organizational branding berat

**Goal:** Bikin informasi resmi terasa modern dan mudah dipahami.

---

## Single Post Quiz Format (Non-Carousel)

> 📄 Contoh soal, caption template, dan topik quiz yang cocok untuk Disdikbud → `references/quiz-patterns.md`

Kadang user minta quiz/konten interaktif tapi lebih cocok **single post** (1 gambar), bukan carousel 7 slide. Kenali sinyalnya:

### Kapan Single Post, Kapan Carousel?
- **Single post** → quiz 1 soal, polling, trivia, "tebak jawaban", quote card, announcement singkat
- **Carousel** → tutorial langkah-demi-langkah, penjelasan konsep kompleks, storytelling, data bertingkat

### Single Post Quiz Template
- **Image**: Pertanyaan + pilihan A/B/C/D (Clay 3D character sebagai ilustrasi pendukung)
- **Caption**: Pertanyaan diulang + "Jawab di komentar! 👇" + CTA
- **Story**: Kunci jawaban + penjelasan singkat (follow-up engagement)

### Copywriting Single Post Quiz
- 1 pertanyaan per gambar, jangan padat
- Pilihan jawaban harus ada 1 yang "bikin kaget" atau counterintuitive (viral hook)
- Max 4 pilihan (A/B/C/D)
- Headline = pertanyaan, bukan judul topik
- Caption: singkat, ajakan komentar, hashtag relevan

### Prompt Adaptation untuk Single Post
- Tetap gunakan style Clay 3D character yang sama
- Karakter clay jadi ilustrasi pendukung (misal: clay character bingung, mikir, tepuk jidat)
- Typography tetap flat 2D modern
- Layout: pertanyaan di atas, pilihan di tengah, karakter clay di samping/bawah
- Aspect ratio: **1:1 (1080x1080)** untuk single post (bukan 4:5 carousel)

### Single Post Design Iterations

Ketika user minta **"buat desain lain"** / **"desain 2"** / **"desain 3"** untuk single post yang sama:

**Pattern:**
- Topik sama, tapi **layout/visual approach berbeda**
- Design 1: character-centric (karakter utama + info cards)
- Design 2: split-screen / comparison layout (before-after, old-new)
- Design 3: hero element focus (giant calendar, giant object, diorama scene)

**What changes between designs:**
- ✅ Layout structure (vertical stacked → horizontal split → centered hero)
- ✅ Visual metaphor (timeline cards → transformation split → calendar flip)
- ✅ Character position (center pointing → 2x same character → beside hero element)
- ❌ Topik/konten inti (tetap sama)
- ❌ Color palette (tetap konsisten)
- ❌ Typography style (tetap flat 2D modern)

**Caption reuse:** Setelah design 2-3 generated, tanya user: "Mau pakai caption design 1, atau buat baru?" — avoid redundant caption generation kalau user cuma explore visual alternatives.

### Caption Length Preference (Single Post)

**Default untuk single post: RINGKAS** (~70-100 kata, ~20-25 baris)

User pattern dari session:
- Caption pertama: detail lengkap (~150-200 kata) → user minta **"caption ringkas"**
- Caption kedua: medium (~100-150 kata) → user minta **"sedikit lebih singkat"**
- Caption ketiga: ringkas (~70-100 kata) → ✅ diterima

**Structure ringkas:**
```
🎉 [Hook — 1 baris]

📅 [Tanggal/konteks — 1 baris]

[Lead — 2-3 baris inti pesan]

📌 [Poin utama dengan emoji bullets — 4-6 baris max]

💡 [Alasan/benefit — 2-3 baris]

⏰ [CTA — 1-2 baris]

—
@handle
#hashtag1 #hashtag2 ... (max 8 tags)
```

**Skip untuk single post:**
- ❌ Paragraf panjang introductory
- ❌ Breakdown detail bertingkat (simpan untuk carousel)
- ❌ Multiple section headers
- ❌ Repetisi informasi yang sudah di visual

**Carousel caption:** Boleh lebih panjang (150-200 kata) karena 7 slide butuh context stitching.

---

## Image Generation Rule

**CRITICAL: JANGAN auto-generate gambar.**

Default output: prompt + structure + concept + caption + CTA — **bukan** gambar.

Generate image HANYA jika user bilang:
- "generate image" / "buat gambarnya" / "render sekarang"
- "visualkan" / "langsung buat gambar" / "create image"

---

## Default Output Format

Setiap request carousel menghasilkan:

1. **Carousel Title** — judul carousel
2. **Total Slides** — 7
3. **Slide-by-Slide Breakdown** — untuk setiap slide:
   - Slide Number
   - Headline (flat 2D typography di gambar)
   - Supporting Text (flat 2D typography di gambar)
   - Visual Description
   - 3D Clay Character Description
   - Layout Description
   - **AI Image Prompt** (copy-paste ready, dengan flat 2D typography block)
4. **Caption** — Instagram caption dengan hashtag
5. **CTA** — call to action
6. **Visual Direction** — color, composition, typography notes

---

## Image Prompt Template

```
3D Clay Character Illustration (Pixar style) — Instagram carousel, portrait 1080x1350px.

COLOR PALETTE: light background #F8FAFC, primary blue #2563EB accents, secondary purple #7C3AED highlights, dark navy #0F172A text, white #FFFFFF surfaces, clean airy atmosphere.

[SLIDE 1 COVER ONLY]
TOP AREA (top 120px): completely empty, plain #F8FAFC — no visual content, no text, no brand tag. This area is reserved for left and right logo placement in post-production (Canva).
SLIDE INDICATOR: positioned just below the 120px header area at top-right — "1/7", small, flat 2D modern sans-serif, dark navy #0F172A 60% opacity. Does NOT overlap the 120px logo area.

HERO VISUAL [full bleed / dari 120px ke bawah untuk cover, full bleed semua sisi untuk slide 2-7]:
[deskripsi 3D clay character dan scene — KARAKTER UTAMA harus 3D clay Pixar style, environment modern/clean]

[SLIDE 2-7: No brand tag. Slide indicator at top-right corner — "X/7", small, flat 2D modern sans-serif, dark navy #0F172A 60% opacity.]

TYPOGRAPHY (flat 2D modern graphic design — NOT 3D, NOT clay, NOT extruded):
HEADLINE (extra bold sans-serif, large scale, deep blue #2563EB, flat 2D clean): "[headline text]"
SUBHEADLINE (semi bold sans-serif, medium, dark navy #0F172A, flat 2D): "[subheadline text]"
BODY (regular sans-serif, small, dark navy #0F172A 80% opacity, flat 2D): "[body text]"
All text is FLAT 2D modern typography — NOT 3D extruded, NOT clay material, NOT sculpted.

FOOTER:
Bottom-left: "@disdikbudsulbar.official" — flat 2D, small, subtle, dark navy #0F172A 60% opacity, text only, no icons
Bottom-right: "Next →" / "Swipe →" (small, flat 2D)

3D CLAY CHARACTER REQUIREMENTS: Pixar-style 3D clay character — rounded body, soft clay material with visible texture, expressive face with big eyes, friendly emotions, volumetric lighting, ambient occlusion contact shadows, subsurface scattering on clay material, depth of field, physical volume and weight. Environment can be modern SaaS style / clean 3D — not necessarily clay. Style: premium 3D render, clean cinematic lighting, modern SaaS aesthetic, generous whitespace, Dribbble featured quality, Behance premium, minimalist composition. No watermark, no QR code, no blur, no cropped elements, no fake logos, no government logos, no progress indicator. NOT flat illustration, NOT 2D, NOT paper cut-out.
```
---

## Prompt Quality Rules

Prompts harus:
- **Highly detailed** — spesifik, bukan vague
- **Cinematic + Clay** — movie-quality descriptors dengan clay material specifics
- **Professionally structured** — logical element order
- **AI model friendly** — works di ChatGPT Image, Midjourney, Leonardo AI, Ideogram, Canva AI
- **Consistent** — same visual direction across all 7 slides
- **Copy-paste ready** — user bisa paste langsung ke AI tool

### Prompt Checklist (10 Elements)

1. **Main subject** — apa yang ada di scene
2. **3D Clay Character** — Pixar-style, rounded, expressive, soft clay material (FOKUS UTAMA)
3. **Character expression** — emosi dan pose (volumetric, dimensional)
4. **Environment** — modern/clean, bukan harus clay
5. **Lighting** — volumetric, ambient occlusion, subsurface scattering
6. **Composition** — depth of field, foreground-background, whitespace
7. **Typography** — FLAT 2D modern sans-serif, BUKAN 3D clay
7. **Branding** — Slide 1: header area 120px kosong untuk logo. Slide indicator di bawah area 120px. Footer kiri: @disdikbudsulbar.official text only.
9. **Render quality** — premium 3D render, clay material texture pada karakter
10. **Aspect ratio** — 4:5 vertical (1080×1350)

### 3D Quality Gate (WAJIB dicek di setiap prompt)
- [ ] Ada keywords: "3D clay character", "Pixar-style", "volumetric", "depth of field"
- [ ] Karakter utama terdeskripsi sebagai 3D clay (volume, shadow, texture)
- [ ] Ada "NOT flat illustration, NOT 2D" di prompt
- [ ] Clay material texture terdeskripsi pada karakter (soft, rounded, expressive)
- [ ] Lighting deskripsi mencakup volumetric / ambient occlusion
- [ ] **Typography = FLAT 2D** (ada block "NOT 3D, NOT clay, NOT extruded")
- [ ] **Text ada di gambar** sebagai flat 2D modern design

---

## Copywriting Rules (Text di Gambar — Flat 2D)

Text dan copywriting DIMASUKKAN ke gambar sebagai flat 2D modern typography:

- Satu slide = satu pesan
- Headline maks 2 baris, maks 3 kata per baris
- Pendek, jelas, swipe-worthy, emotion-driven, mobile-friendly
- **Hindari:** "Di era digital", "Seiring perkembangan zaman", "Sebagaimana diketahui", bahasa birokrasi, paragraf panjang, teks AI-sounding
- **Headline = emotional hook**, bukan judul artikel
- Setiap slide jawab: "Apa satu hal yang harus diingat audiens?"

### Educational Content
- Short sentences
- Visual storytelling
- Progressive learning
- Jangan long paragraphs / bureaucratic language / jargon tanpa penjelasan

---

## Supported AI Models

Prompts optimized for:
- **ChatGPT Image** (GPT Image 2.0) — primary
- **Midjourney** — style parameters
- **Leonardo AI** — model selection notes
- **Ideogram** — text-in-image capable
- **Canva AI** — template integration

---

## Common Pitfalls

1. **Auto-generate tanpa diminta.** Selalu output prompt dulu, tunggu instruksi.
2. **Prompt vague.** Spesifikkan material clay, ekspresi, lighting, environment detail. WAJIB deskripsi 3D volume.
3. **Lupa aspect ratio.** Selalu 4:5 vertical / 1080×1350.
4. **Hasil FLAT bukan 3D.** Selalu include "3D clay character", "Pixar-style", "volumetric lighting", "depth of field", "NOT flat illustration, NOT 2D" di setiap prompt.
5. **Typography jadi 3D clay.** Text WAJIB flat 2D modern sans-serif. Selalu include block "TYPOGRAPHY (flat 2D modern — NOT 3D, NOT clay, NOT extruded)". Kontras antara karakter 3D clay + text flat 2D = visual premium.
5. **Inconsistent visual direction.** Semua 7 slide harus share style, palette, quality.
6. **Skip 120px header space** di slide 1.
7. **Masukkan brand tag/slide indicator di area logo.** Slide 1: area 120px kosong untuk logo. Slide indicator di bawah area 120px. Footer kiri: "@disdikbudsulbar.official" text only, tanpa icon sosmed.
8. **Terlalu banyak text per slide.** Satu ide utama per slide, max 2 baris headline.
9. **Skip visual hierarchy.** Headline → Illustration → Info → Navigation, selalu.
10. **Mixing style karakter dan typography.** Karakter = 3D clay Pixar style. Typography = flat 2D modern. Jangan campur — jangan bikin text jadi 3D clay, dan jangan bikin karakter jadi flat. Kontras ini yang bikin premium.
11. **Kurang whitespace.** 3D Clay style butuh breathing room — jangan padat. Depth of field bantu buat separation.
12. **"Load skill" ≠ "skip skill".** Ketika user bilang "load prompt clay" atau sejenisnya, itu berarti ikuti workflow skill — output per slide satu per satu, bukan langsung tulis semua prompt sekaligus. Skill punya framework step-by-step yang harus diikuti. Jangan bypass proses skill dan buat output manual — user meminta load skill karena ingin output SESUAI format skill.
13. **Blokade image_generate tanpa FAL_KEY.** Jangan coba image_generate kalau FAL_KEY belum ter-set — langsung tanya user mau generate manual (copy-paste prompt ke ChatGPT/Midjourney) atau set FAL_KEY dulu. Membuang token di tool call yang pasti gagal.
14. **Quiz dengan jawaban tidak terverifikasi.** Fakta data (luas wilayah, populasi, tahun berdiri, nama resmi) WAJIB dicek dari sumber otoritatif sebelum dipakai di quiz. Jangan pernah kira-kira. Counterintuitive ≠ salah — pastikan jawaban benar-benar valid dulu. Lihat `references/quiz-patterns.md` untuk data Sulbar terverifikasi dan teknik verifikasi dari Wikipedia.

---

## Verification Checklist

- [ ] Output: title, 7-slide breakdown, prompt per slide, caption, CTA, visual direction
- [ ] Setiap prompt punya 10 elemen wajib
- [ ] Aspect ratio 4:5 (1080×1350)
- [ ] Prompt copy-paste ready untuk target AI model
- [ ] Visual direction konsisten antar slide (FULL 3D clay render, blue-purple palette)
- [ ] Tidak auto-generate gambar
- [ ] Slide 1 ada header space 120px kosong untuk logo kiri/kanan
- [ ] Slide 2-7: slide indicator di kanan atas (di bawah area 120px, tidak menutup logo)
- [ ] Footer kiri: @disdikbudsulbar.official (text only, tanpa icon sosmed)
- [ ] Footer kanan: navigation "Next →" / "Swipe →"
- [ ] Tidak ada brand tag di kiri atas
- [ ] Satu ide per slide, max 2 baris headline
- [ ] Generous whitespace, clean composition
- [ ] Mobile-friendly readability
- [ ] Instagram-ready
- [ ] **Karakter utama = 3D clay Pixar style** (bukan flat/2D)
- [ ] Setiap prompt punya: "3D clay character", "Pixar-style", "volumetric", "depth of field", "NOT flat"
- [ ] **Typography = FLAT 2D modern sans-serif** (bukan 3D, bukan clay)
- [ ] Ada "TYPOGRAPHY (flat 2D modern — NOT 3D, NOT clay)" block di setiap prompt
- [ ] Kontras jelas: karakter 3D clay + text flat 2D
