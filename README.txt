AiRA: GitHub Pages upload instructions

Use the contents of THIS folder for the published website, not the old source ZIP.
1. Sign into the GitHub account that controls aira-consortium.github.io. Use the existing aira-consortium.github.io repository to keep the website address unchanged.
2. In account Settings > Emails, enable Keep my email addresses private and Block command line pushes that expose my email. Keep the public profile email blank. Enable two-factor authentication and store recovery codes privately.
3. Open the existing aira-consortium.github.io repository. Keep this exact repository name and owner; the newsletter links point to https://aira-consortium.github.io/.
4. Upload all the contents of this folder. index.html, assets, original, about, groups, projects, partners, contact join and newsletter must be at the repository root, not inside another folder. Do not upload the ZIP itself. Include .nojekyll; on a Mac, Command-Shift-Period shows hidden files. Commit changes.
5. Open repository Settings > Pages. Under Build and deployment, choose Deploy from a branch, then main and / (root), and Save. Allow several minutes. Use the website link GitHub displays. Enable Enforce HTTPS if offered.
6. Open every navigation page, a member profile and the membership link. Submit one test contact message from the new website and check both Formspree Submissions and your email inbox. Formspree settings must permit AJAX submissions and the new domain; inbox notification delivery is controlled by Formspree and the mail provider, not this static website. Newsletter signup remains disabled until a mailing service is connected. The current issue is included at newsletter/issue-1.html. Its project, contact and website links remain https://aira-consortium.github.io/projects/, https://aira-consortium.github.io/contact/ and https://aira-consortium.github.io/. Uploading the newsletter does not send emails.

The upload contains finished static pages: no build action, account login, database, API key, password, Gmail address, old hosting identifier, Git history, or source maps are required. The Formspree submission endpoint is public by design; it cannot read your inbox. Contact messages go directly to Formspree. Membership applications go to the linked Google Form. Those providers retain submitted data under their own settings.

The member directory includes the requested public names, professional descriptions, countries, and photos, including Petar's public profile. Anyone can view or copy public content and browser code. Hidden photo metadata has been removed without changing the pixels.

Credential checks found no common credential patterns or personal account email in this upload. This is not a penetration test or an absolute security guarantee. Protect GitHub, Formspree and email accounts with unique passwords and two-factor authentication. A compromised GitHub account could change the website or contact destination, even though no inbox credentials are stored here.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
Email privacy: https://docs.github.com/en/account-and-profile/how-tos/email-preferences/setting-your-commit-email-address
