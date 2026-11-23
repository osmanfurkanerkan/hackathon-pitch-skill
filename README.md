# Hackathon Pitch – Claude Skill 🇹🇷

Hackathon ve yarışma sunumları için süreye göre sayılmış pitch metni, slayt akışı, demo senaryosu ve jüri soru bankası hazırlar.

Bu bir [Agent Skill](https://agentskills.io). Claude'a (ve SKILL.md formatını destekleyen diğer yapay zeka ajanlarına) bu işi nasıl iyi yapacağını öğretir. Konuşmanda ilgili bir konu geçtiğinde Claude skill'i kendisi kullanır.

## Örnek kullanım

> Yarın 3 dakikalık final sunumumuz var, jüri kriterleri ekte. Pitch metnini hazırla.

## Kurulum

**Claude.ai / Claude uygulaması:** `hackathon-pitch` klasörünü zip'le ve ayarlardaki skill yükleme bölümünden yükle.

**Claude Code:**
```bash
git clone https://github.com/osmanfurkanerkan/hackathon-pitch-skill.git
cp -r hackathon-pitch-skill/hackathon-pitch ~/.claude/skills/
```

**Diğer ajanlar (Cursor, Codex CLI, Gemini CLI vb.):**
```bash
npx skills add osmanfurkanerkan/hackathon-pitch-skill
```

## Diğer Türkçe skill'ler

- [staj-defteri-skill](https://github.com/osmanfurkanerkan/staj-defteri-skill): staj defteri ve staj raporu
- [sponsorluk-dosyasi-skill](https://github.com/osmanfurkanerkan/sponsorluk-dosyasi-skill): sponsorluk dosyası ve sponsor maili
- [topluluk-etkinlik-skill](https://github.com/osmanfurkanerkan/topluluk-etkinlik-skill): öğrenci topluluğu etkinlik planı
- [hackathon-pitch-skill](https://github.com/osmanfurkanerkan/hackathon-pitch-skill): jüri sunumu ve demo
- [burs-mulakat-skill](https://github.com/osmanfurkanerkan/burs-mulakat-skill): burs ve staj mülakatı hazırlığı
- [guvenlik-tarama-skill](https://github.com/osmanfurkanerkan/guvenlik-tarama-skill): savunma amaçlı kod güvenlik incelemesi

## Katkı

Hata bildirimi ve önerilerin için issue açabilir ya da pull request gönderebilirsin.

## Lisans

[MIT](LICENSE) © 2026 Osman Furkan Erkan
