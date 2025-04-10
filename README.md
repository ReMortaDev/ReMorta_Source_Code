# Welcome to Our Awesome Website Template! 

Are you looking to build a [Neocities](https://neoticies.org) site, but aren't sure where to start?

This template makes it easy to create your own retro-style website. Here's how to add your own stuff:

## 1. Adding Pictures

All your pictures should go into the **`assets/images/`** folder. We've created some subfolders to help you keep things organized:

* **`banners/`**: Put big, wide images that you want at the top of your pages here.
* **`general/`**: Logos, small icons, or any image you use on many different pages go here.
* **`page_specific/`**: If a picture is only for one page, find the folder with that page's name inside here (e.g., `about/` for the About page, `index/` for the homepage) and put the picture there. If a folder for your page doesn't exist, you can create one!
* **`sidebar/`**: Small images that you want to show in the left or right columns of your website.
* **`thumbnails/`**: Smaller versions of your pictures that you might use as previews.

**How to use your pictures on a page:**

When you're editing the `.html` files in the `pages/` folder or the sidebar files in the `partials/` folder, you'll use code like this to show a picture:

```html <img src="/assets/images/your_folder/your_picture.jpg" alt="A description of your picture">```

Replace your_folder with the name of the folder where you put your picture (e.g., general, about), and your_picture.jpg with the actual name of your image file. Make sure the spelling is exactly the same!
## 2. Adding Blog Posts or Articles

If you want to add blog posts or articles, you can either:

    Edit the articles.html file in the pages/ folder directly and write your content there using HTML.
    Put your blog post text files (like .txt files) into the assets/text/articles/ folder. You might need to edit the articles.html file to read and display these text files (this might require a little more technical knowledge).

## 3. Adding Videos and Music

Put your video files in the assets/media/videos/ folder and your music files in the assets/media/audio/ folder. You'll need to use HTML code (like the <video> and <audio> tags) in your .html files to show these on your pages.

## 4. Editing the Menu and Sidebar

    Menu: Open the partials/nav.html file. You'll see lines like <a href="#">Home</a>. Change the # to the actual web address of your pages (e.g., /pages/about.html) and change the text "Home" to what you want the menu link to say.
    Left Sidebar: Edit the partials/sidebar_left.html file to add your own text, images, and links.
    Right Sidebar: Edit the partials/sidebar_right.html file similarly.
    Footer: Edit the partials/footer.html to change the copyright information or add links at the bottom of your site.

Remember to save your changes to the .html files after editing them and then open the index.html file in your web browser to see your website!

If you get stuck, don't be afraid to search online for help with basic HTML (for adding text and images) or ask in online communities! Good luck!

