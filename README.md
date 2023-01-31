# RelyComply Website

Built using [Wordpress](https://wordpress.org/) & [Elementor](https://elementor.com/)

### Blog Categories

Categories can be created under **Posts > Categories**. 

> Make sure to **select one of the parent categories**, since these are used to separate the content on the respective Industries pages:
> - **News and resources** 
> - **Case studies**

New categories need to be added to the blog filter menu, which can be done from **Appearance > Menus**. 
1. **Select a menu to edit**, then click Select.
    - Blog Categories (Case studies)
    - Blog Categories (News and resources)
2. In the sidebar (under the Categories tab), **select the new category** and select **Add to Menu**. To change the positioning of the menu items, drag and drop the menu item to the correct position. 
3. **Save** the menu

![Adding a category to blog filter](/assets/images/category_menu.gif)

### Create a post with a report

A post containing a report needs to be created using Elementor page builder since the report form uses the **Elementor form widget**.

1. Add the report file via **Media > Add New**. Click on the uploaded file and **copy the file URL**.

![Add report file](/assets/images/Post-Upload-Report.gif)

2. Create a new post. **Add the report file URL** under Report File (bottom of the page). Add the post title, select a category, add tags and a featured image (as usual).
3. Add the post content using Elementor page builder by selecting **Edit with Elementor**.

![Add report file URL](/assets/images/Post-Report-File-Name.png)

4. To add text, drag and drop the **Text Editor widget** to add the post text.
    - **Add a drop cap** and set the colour to 'Accent'. 
    - The widget will automatically be placed in a **new container**. Padding (spacing) is added to the container by default. **Change the padding amount to 0**. Note: any additional widgets should be added to the same container, with the exception of the report download form. 

<video width="100%" controls="" muted="" loop="">
  <source src="https://claudia-nydahl.github.io/relycomply/assets/videos/Post-Inserting-Text-min.mp4" type="video/mp4">
</video>

5. To add the report download form, insert the template titled **'Report Form (Section + Widgets)'**. When asked to apply settings, choose **'Don't Apply'**. Give the form a unique name so that form submissions can be differentiated.

<video width="100%" controls="" muted="" loop="">
  <source src="https://claudia-nydahl.github.io/relycomply/assets/videos/Post-Inserting-Report-Form.min.mp4" type="video/mp4">
</video>

6. Incoming **form submissions** can be found under Elementor > Submissions (from the Wordpress dashboard).
7. Additional widgets can be added to the post content. Two pre-styled Global Widgets are available. 
    - Image
    - Blockquote

Add image:

![Add Image](/assets/images/Post-Inserting-Image.gif)

Add blockquote:

![Add Blockquote](/assets/images/Post-Inserting-Blockquote-2.gif)

> Global widgets can be found by navigating to the Global tab from the list of widgets. Global widgets must be unlinked in order to change the content.

### Plugins

The additional features (plugins) added are the following:

- [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/)
    - Adds custom fields to each blog post (Featured toggle & Report File input)
- [LiteSpeed Cache](https://wordpress.org/plugins/litespeed-cache/)
    - Cache and performance optimisation. Purge the cache after making global template changes
- [All in One SEO](https://wordpress.org/plugins/all-in-one-seo-pack/)
    - Adds SEO tools
- [CookieYes](https://app.cookieyes.com/)
    - Adds cookie consent popup & tracks cookies used on the site

> Plugins on the site have been kept to a minimum for performance reasons.

> Plugins need to be updated periodically (ideally once a month). Updates should be tested in the staging environment before being performed on the live site.

### Third-party scripts

The following third-party scripts have been added:

- Google Tag Manager
    - Added to Elementor > Custom Code
