## Accelerated Mobile Pages Beginner Course Step 1

This repo contains the starting point of the AMP Beginner Course. It's just a simple HTML page with no styles at all, and no AMP tags/links/scripts.

However, it contains everything that is needed for the final version of the site at the end of Advanced Exercises (data list, server code, images/assets, etc).

The app is hosted on Glitch at the following address:
https://glitch.com/edit/#!/nosy-leech

A link to the instructions will be provided as soon as they are published. Check back for updates soon.

### Remix this project

If you want to edit, play around and complete the course using this Glitch, you can create your own copy of this project.

Click the “Remix This” button on the top right. This will create a new project that you can edit. You can continue to use this same editor for this and future trainings. Each future training will give you the opportunity to start with a reference version of the solution to that point.

If you have a Glitch account, all the remixed projects will be saved into your account.

### Important task: Add your Glitch URL to the environment valiable

It is important to update the environment variable with your own Glitch project's URL.

_This will make sure that our server knows where to serve our pages from and avoid any CORS issues. If you don't know anything about CORS, don't worry. Just make sure you add your URL there._

* Open the `.env` file from the side menu.

* Add your Glitch's live URL on line 5, without the trailing slash, in quotation marks.
If your current URL is `https://glitch.com/edit/#!/your-glitch`, then the result should look like this:

  **line 5 of `.env` file:**
  ```
  URL="https://your-glitch.glitch.me"
  ```

## Note

This is not an official Google product.

All images are are licensed CC0 - no attribution required.
