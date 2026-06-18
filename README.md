# GetJob 💼
> Precision-engineered career matches, simplified.

GetJob is a high-end, high-performance static job board designed with a crisp, premium light-mode aesthetic inspired by modern digital platforms like Stripe and Linear. 

Built strictly with semantic HTML5, modern CSS variables, and Vanilla JavaScript, the entire application runs flawlessly in the browser without requiring heavy frameworks, external backend servers, databases, or build steps.

## ✨ Premium Features

*   **Zero-Backend Architecture:** Leverages client-side `localStorage` to manage, read, and write job data instantly.
*   **Data Obfuscation:** Admin panel features a multi-layered Base64 and URI compression encoder to protect saved payloads from casual client-side inspection.
*   **Real-Time Deadline Validation:** Automated internal timestamp analysis switches expired jobs to a "Closed" state and freezes action hooks instantly.
*   **Auto-Purge Pipeline:** Cleans up the database automatically by completely scrubbing job listings three days after their deadline passes.
*   **Fluid UI Interactions:** Uses glassmorphic components, fluid background ambient orbs, and native system typography for a lightweight, human-crafted design.
*   **Fully Responsive Layout:** Optimized for high-definition desktop views down to mobile phone viewpoints.

## 📁 File Structure

The entire platform is self-contained within just two lightweight files:
*   `index.html` - The public-facing premium job board feed with real-time keyword filtration.
*   `admin.html` - The authenticated management dashboard used to publish new listings.

## 🚀 Instant Deployment

Because this repository contains only static assets, you can go live globally in under 60 seconds:
1. Push this code to your GitHub repository.
2. Navigate to **Settings** > **Pages**.
3. Under **Build and deployment**, set the source branch to `main` (or `master`) and hit **Save**.
4. Your luxury job board is live at `https://<your-username>.github.io/<your-repo-name>/`
