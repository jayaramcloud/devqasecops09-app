# devqasecops09-app

Your classroom web app. Live at **https://devqasecops09.preparingforinterviews.com**

Pushing to the `master` branch redeploys the site automatically (about a minute).

```bash
git clone https://github.com/jayaramcloud/devqasecops09-app.git
cd devqasecops09-app
npm install
npx wrangler dev        # preview locally at http://localhost:8787
# edit src/index.js, then:
git add -A && git commit -m "my change" && git push
```

Full walkthrough: https://github.com/jayaramcloud/hermes-cloudflare-classroom/blob/master/docs/STUDENT-GUIDE.md
