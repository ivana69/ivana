[build]
  publish = "dist"
  command = "npm run build"

[build.environment]
  NODE_VERSION = "18"

[dev]
  command = "https://liberal-style-ai-find.base44.app"
  port = 3000
  targetPort = 3000


[[redirects]]
  from = "/https://linktr.ee/Ivana_buy"
  to = "https://liberal-style-ai-find.base44.app"
  status = 301
  force = true


[[redirects]]
  from = "/https://linktr.ee/Ivana_buy"
  to = "https://linktr.ee/Ivana_buy"
  status = 301
  force = true


[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200

[build]
  # התיקייה שנטליפיי יציג לעולם
  publish = "dist"
  # הפקודה שבונה את האתר שלך
  command = "npm run build"

[build.environment]
  # גרסת המנוע שתריץ את האתר
  NODE_VERSION = "18"

[dev]
  # הגדרות לתצוגה מקדימה (Preview)
  command = "npm run dev"
  port = 3000
  targetPort = 3000

# קישור (ניתוב) לאתר ה-AI שלך
[[redirects]]
  from = "/ai-find"
  to = "https://liberal-style-ai-find.base44.app"
  status = 301
  force = true

# קישור (ניתוב) ל-Linktree שלך
[[redirects]]
  from = "/links"
  to = "https://linktr.ee/Ivana_buy"
  status = 301
  force = true

# ניטוב כללי - מונע שגיאות 404 בריענון דפים
[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200
