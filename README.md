# I Love Smash Burger — website

Website and online ordering (delivery and pickup) for I Love Smash Burger, Amsterdam.

## Live via GitHub Pages
1. Upload these files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then select `main` and `/ (root)`, and click **Save**.
4. After about a minute the site is live at `https://<username>.github.io/<repo-name>/`.

## Settings
Everything you can change is in the `CONFIG` block at the top of the `<script>` in `index.html`:
- `MADE_BY`: name and link for the footer credit
- `OPEN_MIN` / `CLOSE_MIN`: opening hours
- `MIN_ORDER`, `FREE_DELIVERY`, `MENU_UPCHARGE`: order rules
- `ZONES`: delivery areas by postcode, with fees and delivery times

Menu items and prices are in `ITEMS`.
