TECH MASTERY ROADMAPS — VERCEL DEPLOYMENT

Files included:
- index.html (homepage / Tech Mastery Hub)
- tech_mastery_hub.html
- linux_mastery_365_day_roadmap.html
- networking_mastery_365_day_roadmap.html
- cybersecurity_mastery_365_day_roadmap.html
- vercel.json

EASIEST DEPLOY METHOD (no command line):
1. Extract this ZIP on your computer.
2. Sign in to Vercel and create/import a Git repository containing these files, or use Vercel's dashboard upload/deploy option if available on your account.
3. Ensure the project root is the folder containing index.html.
4. Use the Other framework preset / static site settings if asked. No build command is needed; the output directory is the project root (./).
5. Deploy, then open the provided *.vercel.app URL.

RECOMMENDED GIT METHOD:
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root (not the ZIP itself).
3. In Vercel, choose Add New Project and import that repository.
4. Keep framework preset as Other, leave build command empty, set output directory to . (or leave default if it correctly detects the static site), then deploy.

Notes:
- Keep all four roadmap HTML files in the same root folder so navigation links work.
- External learning links require internet access.
- Progress checkboxes use browser localStorage and are saved per browser/device.
- This package does not contain secrets or environment variables.
