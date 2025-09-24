# PORTO
This is a Repo for my Portofolio

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

Setup github repo first on the machine

for credentials, 
1. Create an ssh key using:
    ssh-keygen -t TYPE_HERE_NAME -C "your_email@example.com"
2. Start the SSH agent and add your key:
    eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_TYPE_HERE_NAME
3. Copy the public key to your clipboard:
    cat ~/.ssh/id_TYPE_HERE_NAME.pub
4. Add it to GitHub:
    Go to GitHub → Settings → SSH and GPG keys
    Click New SSH key → paste your key → Save
5. Test your connection:
    ssh -T git@github.com
6. Now you can use SSH in your repos:
    Make sure your repo’s remote uses the SSH URL instead of HTTPS:
      git remote -v
    If you see something like:
      origin  https://github.com/username/repo.git (fetch)
      origin  https://github.com/username/repo.git (push)
    Change it to SSH:
      git remote set-url origin git@github.com:username/repo.git

That was for configuring git from local





