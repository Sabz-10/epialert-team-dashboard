# EpiAlert Team Command Center

## Open locally
Open `index.html` in a browser.

## Publish free with GitHub Pages
1. Create a GitHub repository named `epialert-team-dashboard`.
2. Upload `index.html` and this README.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, then Save.
6. Copy the published URL shown on the Pages screen and share it with Sabari, Surya, and Judith.

## Checklist synchronization
This version saves ticks in the current browser using local storage. Export/Import transfers a JSON snapshot manually. It does not sync live between devices. For true shared checkboxes, add a shared database such as Supabase/Firebase with authentication and access rules, or use GitHub Projects for live shared task tracking. Never put database secret keys in public frontend code.
