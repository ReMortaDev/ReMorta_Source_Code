# Welcome to Your Awesome Website Template!

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

```html
<img src="/assets/images/your_folder/your_picture.jpg" alt="A description of your picture">