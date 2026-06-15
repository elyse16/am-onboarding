# AM Onboarding Hub

Static site for the TLDR Account Manager onboarding hub (program schedule, reference data, AM playbook, resources, exercises, SMEs). Forked from the [AE Sales Onboarding Hub](https://github.com/elyse16/ae-onboarding) for the post-sale AM motion.

## Repository

Remote: [https://github.com/elyse16/am-onboarding](https://github.com/elyse16/am-onboarding)

## Publish with GitHub Pages

1. From this folder on your machine (first time only: add remote and push):

```bash
cd "/Users/elysewolin/Documents/People/AM Onboarding"
git remote add origin https://github.com/elyse16/am-onboarding.git
git push -u origin main
```

If `origin` already exists with a different URL:

```bash
git remote set-url origin https://github.com/elyse16/am-onboarding.git
git push -u origin main
```

2. On GitHub: **Settings → Pages → Build and deployment → Source**: choose **Deploy from a branch**, branch **main**, folder **/ (root)**.
3. After a minute, the site will be at **https://elyse16.github.io/am-onboarding/**.

To update the hub, replace `index.html` with a new export, commit, and push.
