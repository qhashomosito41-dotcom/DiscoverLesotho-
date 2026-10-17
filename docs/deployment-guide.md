# Free Hosting and Deployment Guide

The website is static and can be hosted on a free subdomain. You do not need to purchase a custom domain.

## Option A: GitHub Pages

1. Create or sign in to a GitHub account.
2. Create a new repository for the project.
3. Upload the project files and folders, preserving the directory structure.
4. Open the repository's **Settings**.
5. Open **Pages** in the repository settings.
6. Under the build/deployment source, choose deployment from a branch if that option is available.
7. Select the branch containing the site files and the root (`/`) folder, then save.
8. Wait for GitHub Pages to publish the site.
9. Open the URL shown in the Pages settings.
10. Test the public page, CSS, favicon, navigation, and images.

If the project is hosted in a repository subpath, verify that all local asset links are relative. The current project uses relative CSS and favicon paths.

## Option B: Netlify

1. Create or sign in to a Netlify account.
2. Choose the option to add or deploy a new site.
3. Either connect a Git repository or use the manual deploy/upload workflow offered by Netlify.
4. Upload the project folder's site files, including `index.html`, `css/`, and `assets/`.
5. Wait for deployment to finish.
6. Open the generated Netlify subdomain.
7. Test the deployed page from a private browser window or another device.

## Post-deployment checks

- Open the root URL and confirm the page loads.
- Confirm CSS loads correctly.
- Test all navigation links and CTA buttons.
- Test the mobile navigation.
- Check images and favicon.
- Submit the demo form with invalid and valid values.
- Confirm the form never claims to send a real enquiry.
- Test at a mobile viewport and a desktop viewport.
- Check the browser console for errors.
- Save the exact public URL for the assignment presentation and submission.

## Important limitations

Do not claim the site has been deployed until the host provides a working public URL. The demo form does not deliver enquiries. External images require an internet connection and may be subject to their own usage terms.
