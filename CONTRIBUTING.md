# Contributing

Thank you for your interest in contributing to Awesome Gemara! This guide will help ensure your contributions are reviewed smoothly.

## Developer Certificate of Origin (DCO)

All contributors must sign off on their commits. This certifies that you wrote or have the right to submit the work you're contributing. By contributing, you agree to the [Developer Certificate of Origin](https://developercertificate.org/).

To sign off on your commits, use the `-s` flag:
```bash
git commit -s -m "Add amazing resource"
```

Or add this line to your commit message:
```
Signed-off-by: Your Name <your.email@example.com>
```

## Before You Submit

To help us review your PR quickly, please check these common issues:

- ❌ Adding multiple resources in one PR (please submit one resource per PR)
- ❌ Duplicate of an existing entry or recently-closed PR
- ❌ Resource placed under an inappropriate category
- ❌ Project is archived or abandoned (no commits in 12+ months)
- ❌ Not directly related to Gemara or GRC automation
- ❌ Resource is not publicly accessible

## What We're Looking For

We want to include resources that are valuable to the Gemara community.

Here's what makes a great addition:
1. **Gemara-related**: Directly uses, implements, or supports Gemara
2. **Active**: Commits within the last 12 months (unless it's documentation or a stable standard)
3. **Documented**: Clear README or documentation with examples and use cases

## Entry Format Reference

Here are some examples of how to format your entries:

### Standard Entry

```markdown
- [Resource Name](https://link-to-resource.com) - Brief description ending with period.
```

### Entry with Additional Context

```markdown
- [Resource Name](https://link-to-resource.com) - Brief description. Additional context if needed.
```

### Entry with Related Resource

```markdown
- [Resource Name](https://link-to-resource.com) - Brief description.
 - [Related Resource](https://related-link.com)
```

### Subcategory Format

```markdown
- Subcategory Name

  Description of subcategory.

- [Resource](url) - Description.
```

## Adding a New Section

If you think we need a new category, great! Here's how to add it:

1. Add a section description: Brief explanation of what belongs in this section
2. Add the section title to the Table of Contents in README.md
3. Keep sections in logical order (Project Resources first, then Tools, Libraries, etc.)
4. Make sure the section is necessary and not redundant with existing sections

## Questions?

If you're unsure whether a resource should be included, feel free to open an issue to discuss it first!
