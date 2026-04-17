# ──────────────────────────────────────────────────────────────────────────────
# site.md — Site configuration
# Fill in the fields below, then run:
#   python /path/to/SiteGenerator/generate.py /path/to/this-folder
# ──────────────────────────────────────────────────────────────────────────────


# ── Identity ──────────────────────────────────────────────────────────────────

name: "Gravy Dave's Diner"
github: "https://github.com/djbrieck/gravy-daves-cafe"


# ── Operator (who runs this unofficial site) ──────────────────────────────────

operator: "Brieck's Pro"
operator_url: "https://brieckspro.com/"
operator_support_url: "https://brieckspro.com/value-for-value/"        # optional — remove line if not needed


# ── Favicon ───────────────────────────────────────────────────────────────────
# letter    : single character shown in the favicon square
# font      : any Google Fonts name (for reference only — PIL uses system fonts)
# color     : text color  (#rrggbb)
# background: square background color (#rrggbb)

favicon:
  letter: "G"
  font: "Georgia"
  color: "#1c352d"
  background: "#ff878d"


# ── Contact ───────────────────────────────────────────────────────────────────

location: "359 N Main St, Union, OR 97883"
email: ""
phone: "(541) 624-0244"


# ── Hours ─────────────────────────────────────────────────────────────────────
# One line per entry, e.g. "Monday - Friday: 9AM to 5PM"

hours:
  - "Monday - Saturday: 8:00AM to 2:00PM"
  - "Sunday: Closed"


# ── Links ─────────────────────────────────────────────────────────────────────
# Social media, review sites, etc.

links:
  - label: "Facebook: Gravy Daves Dinner"
    url: "https://www.facebook.com/profile.php?id=61588528673167"


# ── Menu ──────────────────────────────────────────────────────────────────────
# Links to menu files (PDF, HTML) or an external menu page.
# Remove this section entirely if not needed.

menu:
  - label: "Menu - PDF"
    url: "docs/GravyDavesMenu.pdf"
  - label: "Menu - Plain Text"
    url: "docs/menu.html"
