# Damgalio — Claude notları

## Ajanlar (agency-agents)
`.claude/agents/` klasöründe [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
koleksiyonundan (commit `b859c51`) Damgalio/Masalio için seçilmiş 59 uzman alt ajan kurulu (oyun, GIS, sağlık, Çin pazarı vb. alakasız olanlar çıkarıldı). Claude Code bunları proje ajanları
olarak otomatik yükler. Uygun bir uzman varsa (ör. frontend, UI/UX, güvenlik, test, pazarlama)
işi o ajana yönlendir.

Güncellemek için:
```bash
git clone --depth 1 https://github.com/msitarzewski/agency-agents.git /tmp/agency-agents
/tmp/agency-agents/scripts/install.sh --tool claude-code --path "$PWD/.claude/agents" --no-interactive  # sonra alakasızları tekrar sil
```
