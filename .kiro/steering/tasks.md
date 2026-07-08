# Common Tasks

## When to Apply
When performing routine operations on this project.

## Add New Member
1. Get photo (JPG, ~200KB max) → save to `assets/members/firstname-lastname.jpg`
2. Copy the appropriate template from `templates.md` (Golden Jacket, Challenger, or Alumni)
3. Fill in: name, city, state code, LinkedIn URL
4. Insert before the corresponding `<!-- END_* -->` comment
5. Do NOT manually set `card-number` — CI/CD auto-numbers on deploy
6. Update map pins if new city/region is represented

## Add New Article
1. Copy article template from `templates.md`
2. Fill in: date, author, URL, title, description
3. Insert before `<!-- END_ARTICLES -->`

## Promote Challenger to Golden Jacket
1. Move their card from `#challengers` section to `#members` section (before `<!-- END_GOLDEN_JACKETS -->`)
2. Change class from `member-card challenger` to `member-card`
3. Change tags from `NN/12 Certifications` + `Challenger` to `Golden Jacket` + `Member`
4. Change certified line to `All 12 AWS Certifications ✓`
5. Remove the `style="color:#fff;font-weight:700;"` from certified div
6. Remove `card-number` — CI/CD will assign new number

## Validation Checklist (before any PR)
- [ ] All images have `alt` text
- [ ] All cards have `data-state` attribute
- [ ] LinkedIn URLs are valid and use `target="_blank"`
- [ ] No hardcoded card-numbers on new cards
- [ ] No AWS credentials or account IDs in code
- [ ] Translations object updated if new user-facing text added (EN + ES)
