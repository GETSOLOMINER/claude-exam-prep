# ClaudeExamPrep.com

152 CCA (Claude Certified Architect) practice questions — organized by exam domain with detailed explanations.

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your GitHub repo
4. Vercel auto-detects the config — click **Deploy**
5. Add your custom domain (`claudeexamprep.com`) in Project Settings → Domains

## Folder Structure

```
├── public/
│   ├── index.html                                      # Landing page
│   ├── ClaudeExamPrep_Free_Sample_10_Questions.pdf     # Free sample (lead magnet)
│   └── ClaudeExamPrep_152_CCA_Practice_Questions.pdf   # Paid product
├── vercel.json                                          # Vercel config
├── package.json
└── README.md
```

## Setup Checklist

- [ ] Buy domain: `claudeexamprep.com` ($11.25/yr on Vercel)
- [ ] Set up payments: Create [Gumroad](https://gumroad.com) product, replace Buy Now button href
- [ ] Set up email: Connect [ConvertKit](https://convertkit.com) or [Mailchimp](https://mailchimp.com) to the email form
- [ ] Remove the full PDF from `public/` once Gumroad handles delivery (so it's not freely downloadable)
- [ ] Have a CCA-certified person review the questions for accuracy
