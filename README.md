# Gitting Gud Practice 🎮

Your own repo to follow along with the Git and GitHub demo. Do each step right after you see it on screen.

Stuck at any point? **Raise your hand.** An assistant dev will come to you.

**Before you start:** you need a GitHub account and GitHub Desktop, signed in.

---

## Part 1: Make your own copy

1. On this page, click the green **Use this template** button → **Create a new repository**.
2. Name it `gitting-gud-practice`, keep it **Public**, then click **Create repository**.
3. You're now on *your* copy. Check that the top left shows your username, not the workshop's.

## Part 2: Save and share your work

4. **Clone.** On your repo, click the green **Code** button and copy the link. In GitHub Desktop: **File → Clone repository → URL** tab → paste → **Clone**.
5. **Open it.** In GitHub Desktop: **Repository → Open in Visual Studio Code**. Also **Repository → Show in Explorer** (Finder on Mac) and double-click `index.html` to open it in your browser.
6. **Edit.** In `index.html`, add a snack under Nova. Copy the Nova line and change the name:
   ```html
   <li>Piattos</li>
   ```
   Save, then refresh the browser.
7. **Commit.** In GitHub Desktop, type a summary like `Add Piattos to snack list`, then click **Commit to main**.
8. **Check GitHub.** Refresh your repo on github.com. Your snack isn't there yet. Commits stay on your laptop until you push.
9. **Push.** Click **Push origin**. Refresh github.com. Now it's there.
10. **Pull.** On github.com, open `index.html`, click the pencil icon, add another snack, then **Commit changes**. In GitHub Desktop, click **Fetch origin**, then **Pull origin**. The new snack appears in VS Code.

## Part 3: Work on a branch

11. **Branch.** In GitHub Desktop: **Current branch → New branch** → name it `add-my-card` → **Create branch**.
12. **Edit your card.** In `index.html`, replace `Your Name` and the fun fact with your own. Save and refresh the browser.
13. **Commit** with the summary `Add my profile card`.
14. **Checkout.** Switch to **main** (Current branch → main) and refresh the browser: your card is gone. Switch back to `add-my-card`: it's back.
15. **Publish.** Click **Publish branch**.
16. **Pull request.** Click **Create Pull Request**. On github.com, click **Create pull request**.
17. **Merge.** Click **Merge pull request → Confirm merge**. Your card is now part of main.
18. **Back to main.** In GitHub Desktop: switch to **main** → **Fetch origin** → **Pull origin**.

You did the whole loop: pull, branch, edit, commit, push, pull request, merge, pull. 🎉

---

## Bonus: Make a merge conflict on purpose

1. On github.com, edit `index.html` and change the **Favorite snack** line to something else. Commit.
2. In VS Code (on main), change the **same line** to something different. Save and commit.
3. In GitHub Desktop: **Fetch origin → Pull origin**. Git says there's a conflict.
4. Open the file in VS Code. Click **Accept Current Change** or **Accept Incoming Change**. Save.
5. Back in GitHub Desktop, finish the merge, then **Push origin**.

Conflicts are normal. Nothing broke. Git just asked you to choose.
