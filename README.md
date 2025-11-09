# 🎬 UGC Machine - AI-Powered Ad Replication System
Transform winning ads into custom video content with AI-driven analysis and Sora 2 prompts.

---

## 🎥 Video Guide
[![Watch the Setup Tutorial](https://img.youtube.com/vi/5iZbwuVBMGk/maxresdefault.jpg)](https://youtu.be/5iZbwuVBMGk)

**[👉 Watch Full Tutorial]([https://youtu.be/5iZbwuVBMGk](https://youtu.be/5iZbwuVBMGk))**

**[🎁 Join FREE Skool Community - Get 50+ AI Agent Templates](https://www.skool.com/chase-ai-community)**

---

## ⚡ How It Works
```
🎯 Find Ad → 🔍 Gemini Analysis → 📝 Template Creation → 🎨 Brand Adaptation → 🎬 Sora 2 Prompts
```

---

## 🎯 What It Does
- 🔍 **Analyze winning ads** - Forensic breakdown of viral UGC content
- 📋 **Create templates** - Extract replicable patterns from successful ads
- 🎨 **Adapt messaging** - Integrate your product and brand voice
- 🎬 **Generate Sora prompts** - Production-ready video generation instructions
- ⚡ **Scene consolidation** - Intelligent 10-15 second clip optimization
- 🎭 **Character consistency** - Maintain visual coherence across scenes

---

## 🛠️ Requirements
| Service | Cost | Purpose |
|---------|------|---------|
| Gemini API | Free tier available | Video analysis |
| OpenRouter (Claude Sonnet 4.5) | ~$3-15/mo | Prompt generation |
| Airtable | Free tier available | Data management |
| n8n | Free (self-hosted) | Workflow automation |

---

## 🚀 Quick Setup
1. **Copy Airtable Base** - [Get template here](https://airtable.com/appgNk77WMStSwW5y/shrDXKxecubCVzte4)
2. **Import workflow** to n8n
3. **Connect APIs:**
   - [Gemini API](https://docs.n8n.io/integrations/builtin/credentials/google/)
   - [Airtable](https://docs.n8n.io/integrations/builtin/credentials/airtable/)
   - OpenRouter (Claude Sonnet 4.5)
4. **Update credentials** in workflow nodes
5. **Configure Airtable** base ID and table references
6. **Test with sample ad** 🎉

---

## 📊 Workflow Architecture

### **Stage 1: Video Analysis (Gemini)**
```
📹 Input: Ad URL from Meta Ad Library
🔍 Output: Forensic scene-by-scene breakdown
```
- Camera specifications and movements
- Lighting and cinematography details
- Character descriptions and performance notes
- Dialogue transcription with delivery notes
- Editing style (jump cuts, continuous takes)
- Audio environment and ambience

### **Stage 2: Prompt Generation (Claude Sonnet 4.5)**
```
📋 Input: Video analysis + Your product messaging
🎨 Output: Sora 2-ready video prompts
```
- Intelligent scene consolidation (10-15 sec clips)
- Adapted dialogue maintaining original style
- Product visual swapping
- Character consistency preservation
- Technical specifications for Sora 2

---

## 🎬 Perfect For
📱 UGC Creators | 🛍️ E-commerce Brands | 📺 Marketing Agencies | 🎥 Content Studios | 💼 DTC Companies

---

## 💡 Key Features

### **Forensic Analysis**
✅ Frame-by-frame cinematography breakdown  
✅ Exact dialogue transcription with filler words  
✅ Character appearance documentation  
✅ Jump cut and editing style detection  
✅ Audio environment mapping  

### **Smart Adaptation**
✅ Copywriting-quality dialogue rewriting  
✅ Brand voice consistency  
✅ Word count matching (±10 words)  
✅ Energy and pacing preservation  
✅ Product visual swapping  

### **Sora 2 Optimization**
✅ 10-15 second clip consolidation  
✅ Scene grouping logic  
✅ Duration validation (prevents content inflation)  
✅ JSON-formatted output for easy integration  
✅ Character cameo support (@username)  

---

## 📋 Airtable Structure
**Fields:**
- **Name** - Ad identifier
- **Original Ad URL** - Source video link
- **Your Product Message** - Brand messaging and product details
- **Character** - Description or Sora 2 cameo (@username)
- **Scene 1-5 Prompts** - Generated Sora 2 instructions
- **Generate Prompts** - Button trigger for workflow

---

## ⚙️ Configuration Options

### **Critical Constraints**
```javascript
maxPromptDuration: 15         // Sora 2 maximum (10 or 15 sec)
maxTotalOverage: 10           // Max seconds over original length
sceneSplitThreshold: 15       // When to break scenes
```

### **Gemini Analysis**
- Ignore on-screen text and captions
- Group uninterrupted B-roll
- Capture exact dialogue with filler words
- Document jump cuts and editing style

### **Claude Prompt Generation**
- Match original word count (±10 words)
- Preserve sentence structure and rhythm
- Maintain emphasis patterns
- Adapt product references only

---

## 🎯 Use Cases

| Industry | Application |
|----------|-------------|
| 🏋️ Fitness | Supplement testimonials |
| 💄 Beauty | Skincare routines |
| 🍽️ Food | Recipe/product demos |
| 👕 Fashion | GRWM content |
| 🏠 Home | Product unboxings |

---

## 🌟 Benefits

| Traditional Method | UGC Machine |
|-------------------|-------------|
| ❌ $500-5K per video | ✅ $50-200 with Sora 2 |
| ❌ 2-4 week production | ✅ Same day turnaround |
| ❌ Manual scriptwriting | ✅ Auto-adapted copy |
| ❌ Hire actors/crew | ✅ AI-generated talent |
| ❌ One-off content | ✅ Scalable templates |

---

## 🔧 Advanced Features

### **Dialogue Adaptation Engine**
- Matches original pacing (WPM calculation)
- Preserves conversational imperfections
- Maintains emotional arc structure
- Applies brand voice guidelines

### **Scene Intelligence**
- Natural grouping logic (DTC + B-roll)
- Major break point detection
- Duration optimization (10 vs 15 sec decisions)
- Part splitting for long scenes

### **Quality Control**
- Total duration validation
- Content inflation prevention
- Character consistency checks
- Technical spec preservation

---

## 📝 Product Messaging Template
```
Product Name: [Your Product]
Product Category: [Category]
Visual Description: [Detailed Sora 2 specs]

Brand Voice:
- Tone: [Confident/Casual/Educational]
- Language Style: [Professional/Conversational]
- Key Phrases: [Example messaging]

Key Benefits:
1. [Primary benefit with proof]
2. [Secondary benefit]
3. [Tertiary benefit]

Target Audience:
- Demographics: [Age/interests]
- Pain Points: [Problems you solve]
- Goals: [What they want to achieve]
```

---

## 🎬 Output Format

**JSON Structure:**
```json
{
  "prompt_1": "# PROMPT 1 (Duration: 15 seconds)\n\n**Overview:** ...\n\n**Sora Parameters:** ...",
  "prompt_2": "# PROMPT 2 (Duration: 10 seconds)\n\n...",
  "prompt_3": "..."
}
```

Each prompt includes:
- Duration specification (10 or 15 sec)
- Scene overview and style notes
- Complete Sora 2 parameters
- Sub-scene cinematography details
- Character descriptions
- Adapted dialogue with delivery notes

---

## 🚨 Important Notes

⚠️ **Copyright Compliance** - Only analyze ads you have rights to replicate  
⚠️ **Duration Rules** - Never exceed original length by >10 seconds  
⚠️ **Dialogue Matching** - Maintain original word count and structure  
⚠️ **Character Cameos** - Use @username format for Sora 2 consistency  
⚠️ **Technical Specs** - Preserve all cinematography details exactly  

---

## 🏆 Credits
**Created by [Chase AI](https://www.skool.com/chase-ai)**

**Ready to scale your content production? Join [Chase AI+](https://www.skool.com/chase-ai) for advanced training on building AI agencies.**

---

**Now go create viral content at scale!** 🚀🎬
