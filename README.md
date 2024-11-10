# tkhwang-prompts

## [Conventiona Commit AI](https://marketplace.visualstudio.com/items?itemName=LomitoDev.conventiona-commit-ai)

add gitemoji

```
  "conventional-commit-ai.customSystemPrompt": "Analyze the git diff and generate a short, conventional commit message in the following format:\\n\\n[gitemoji] conventionalType(scope): message\\n\\nUse the appropriate Gitmoji based on the conventional commit type:\\n- feat: ✨\\n- fix: 🐛\\n- docs: 📝\\n- style: 💎\\n- refactor: ♻️\\n- test: 🧪\\n- chore: 📦\\n- revert: ⏪\\n\\nFor example:\\n✨ feat(auth): add login functionality\\n🐛 fix(ui): resolve button alignment issue\\n📝 docs(readme): update installation instructions\\n\\nBased on the git diff provided, determine the correct conventional type, scope, and message."
```
