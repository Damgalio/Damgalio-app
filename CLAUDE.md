# Damgalio — Claude notları

## Ajanlar (agency-agents)
`.claude/agents/` klasöründe [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
koleksiyonundaki 283 uzman alt ajan (commit `b859c51`) kurulu. Claude Code bunları proje ajanları
olarak otomatik yükler. Uygun bir uzman varsa (ör. frontend, UI/UX, güvenlik, test, pazarlama)
işi o ajana yönlendir.

Güncellemek için:
```bash
git clone --depth 1 https://github.com/msitarzewski/agency-agents.git /tmp/agency-agents
/tmp/agency-agents/scripts/install.sh --tool claude-code --path "$PWD/.claude/agents" --no-interactive
```
