# MalScan

**MalScan** — zərərli fayl analizinə yönəlmiş statik analiz vasitəsi (web app). Fayllar heç vaxt icra edilmir — yalnız statik metodlarla analiz olunur.

## 🎯 Xüsusiyyətlər
- Fayl hash-lərinin hesablanması (MD5, SHA1, SHA256)
- PE header analizi
- String extraction (mətn çıxarışı)
- Entropy hesablanması (şifrələnmiş/packed faylların aşkarlanması üçün)
- YARA qaydaları ilə skan
- VirusTotal API inteqrasiyası — hash reputasiya yoxlaması
- Çoxdilli dəstək: 🇬🇧 English / 🇦🇿 Azərbaycan / 🇷🇺 Русский

## 🛠️ İstifadə olunan texnologiyalar
- Emergent.ai (build platform)
- [backend/frontend stack-i buraya əlavə et]
- VirusTotal API
- YARA

## ⚠️ Xəbərdarlıq
Bu tətbiq **yalnız statik analiz** aparır — heç bir upload edilmiş fayl icra olunmur. Analiz üçün nəzərdə tutulmuş fayllarla ehtiyatlı davranın və onları izolə edilmiş mühitdə saxlayın.

## 🚀 Quraşdırma
\`\`\`bash
# clone
git clone <repo-url>
cd malscan

# addımlar buraya
\`\`\`

## 📌 Gələcək planlar
- Google Gemini API inteqrasiyası (VirusTotal rate limit üçün alternativ)
- Əlavə statik analiz metodları

##Müəllif👤
Rza Asadov // https://github.com/rzasadoff85




