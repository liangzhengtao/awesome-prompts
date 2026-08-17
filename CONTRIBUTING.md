# Contributing to Awesome Prompts

Thank you for your interest in contributing! 🎉

We welcome contributions of all kinds: new prompts, improvements to existing ones, bug fixes, translations, and more.

## How to Contribute

### 1. Adding a New Prompt

1. Fork the repository
2. Create a new branch: `git checkout -b add/my-new-prompt`
3. Choose the appropriate category folder under `prompts/`
4. Create or edit the markdown file following our template:

```markdown
### N. Prompt Title

\```
[Prompt text with [VARIABLES] in brackets]
\```
```

5. Ensure your prompt includes:
   - A clear title
   - The prompt text with `[VARIABLES]` for customizable parts
   - At least one example use case in the description above

6. Submit a Pull Request

### 2. Improving Existing Prompts

1. Fork and branch: `git checkout -b improve/prompt-name`
2. Make your changes
3. Explain **why** the change improves the prompt in your PR description
4. Submit a Pull Request

### 3. Reporting Issues

- Use the [Bug Report](https://github.com/liangzhengtao/awesome-prompts/issues/new?template=bug_report.md) template
- Include the prompt file and line number
- Describe what's wrong and suggest a fix if possible

## Prompt Quality Guidelines

### ✅ Good Prompts

- **Specific**: Clear about what output is expected
- **Structured**: Use numbered lists, headers, or sections for output format
- **Variables**: Use `[VARIABLES]` in brackets for customizable parts
- **Context-aware**: Include instructions about tone, audience, and constraints
- **Tested**: You've actually used the prompt and verified it works well

### ❌ Avoid

- Vague instructions ("write something about AI")
- Missing output format specifications
- Prompts that are too long (> 2000 words) — break them into sub-prompts
- Prompts with hardcoded values that should be variables
- Prompts that only work with one specific AI model

## File Naming Convention

- Use kebab-case: `my-prompt-file.md`
- Bilingual: primary language is Chinese for Chinese-named categories, English for English sections
- Each category folder name is bilingual: `编程开发/`, `内容创作/`, etc.

## Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

## Questions?

Open a [Discussion](https://github.com/liangzhengtao/awesome-prompts/discussions) if you have questions about contributing.

Thank you for making Awesome Prompts better! 🚀
