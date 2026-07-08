# Templates

## When to Apply
When adding new members, articles, videos, or events to the site.

## Member Card (Golden Jacket)
```html
<div class="member-card" data-state="XX">
  <img src="assets/members/FILENAME.jpg" alt="FULL NAME" class="photo">
  <h3>FULL NAME</h3>
  <div class="location">CITY, Colombia</div>
  <div class="tags">
    <span class="tag">Golden Jacket</span>
    <span class="tag">Member</span>
  </div>
  <div class="certified">All 12 AWS Certifications ✓</div>
  <div class="socials">
    <a href="https://www.linkedin.com/in/PROFILE/" target="_blank">in</a>
  </div>
</div>
```
Insert before `<!-- END_GOLDEN_JACKETS -->`

## Member Card (Challenger)
```html
<div class="member-card challenger" data-state="XX">
  <img src="assets/members/FILENAME.jpg" alt="FULL NAME" class="photo">
  <h3>FULL NAME</h3>
  <div class="location">CITY, Colombia</div>
  <div class="tags">
    <span class="tag">NN/12 Certifications</span>
    <span class="tag">Challenger</span>
  </div>
  <div class="certified" style="color:#fff;font-weight:700;">X away from Golden Jacket 🔥</div>
  <div class="socials">
    <a href="https://www.linkedin.com/in/PROFILE/" target="_blank">in</a>
  </div>
</div>
```
Insert before `<!-- END_CHALLENGERS -->`

## Member Card (Alumni)
```html
<div class="member-card alumni" data-state="XX">
  <img src="assets/members/FILENAME.jpg" alt="FULL NAME" class="photo">
  <h3>FULL NAME</h3>
  <div class="location">CITY, Colombia</div>
  <div class="tags">
    <span class="tag">Alumni</span>
    <span class="tag">Member</span>
  </div>
  <div class="certified">All 12 AWS Certifications ✓</div>
  <div class="socials">
    <a href="https://www.linkedin.com/in/PROFILE/" target="_blank">in</a>
  </div>
</div>
```
Insert before `<!-- END_ALUMNI -->`

## Article Entry
```html
<div style="background:var(--bg2);border:1px solid var(--border);border-radius:12px;padding:20px 24px;margin-bottom:12px;transition:all 0.3s;" onmouseover="this.style.borderColor='rgba(255,215,0,0.4)'" onmouseout="this.style.borderColor='var(--border)'">
  <p style="color:var(--text-muted);font-size:0.7em;margin-bottom:4px;"><span style="background:rgba(255,215,0,0.15);color:var(--gold);padding:2px 8px;border-radius:4px;font-size:0.9em;font-weight:600;margin-right:6px;">📝 Article</span> Mon DD, YYYY · <span style="color:var(--gold);font-style:italic;">AUTHOR NAME</span></p>
  <a href="URL" target="_blank" rel="noopener noreferrer" style="color:var(--gold);font-weight:700;font-size:1em;text-decoration:none;">TITLE</a>
  <p style="color:var(--text-muted);font-size:0.85em;margin-top:6px;">DESCRIPTION</p>
</div>
```
Insert before `<!-- END_ARTICLES -->`

## Available Role Tags
- `<span class="tag role-founder">Founder</span>`
- `<span class="tag role-cofounder">Co-Founder</span>`
- `<span class="tag role-cb">AWS Community Builder</span>`
- `<span class="tag role-ugleader">AWS UG Leader</span>`
- `<span class="tag role-ambassador">AWS Ambassador</span>`
- `<span class="tag role-speaker">Speaker</span>`
