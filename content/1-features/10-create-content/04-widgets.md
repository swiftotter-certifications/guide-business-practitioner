### Widgets

Widgets are a way to inject content into targeted locations on an Adobe Commerce website (on a more global basis, instead of one-off placements). The sample data heavily utilizes widgets to display the image blocks. **_This is probably one of the most underutilized features in Magento._**

Ultimately, this is easily confused with CMS content widgets (as I call it). Content widgets are code directives that are injected into the WYSIWYG editor.

Widgets are managed in Content > Widgets. They are available in both Open Source and Commerce.

To create a widget, you first specify the type of the widget (this happens to be the same list as used in the WYSIWYG editor). Then, specify the theme.

The widget is assigned to specific store views (or all store views).

Finally, you identify where to display the widget:

* Anchor categories (all or specific categories)
* Non-anchor categories (all or specific categories)
* All product types (all or specific products)
* Simple Product (all or specific products)
* Virtual Product (all or specific products)
* Configurable Product (all or specific products)
* Downloadable Product (all or specific products)
* Gift Card (all or specific products)
* Grouped Product (all or specific products)
* All Pages
* Specified Page (select page)
* Page Layouts (select custom page layout)

Once you determine on what pages to display the widget, the last thing to do is to determine the container (where on the page to display the widget).

You can also configure the options for the widget in the Widget Options tab.

**Further reading:**

* [Widget Static Block](https://docs.magento.com/user-guide/cms/widget-static-block.html)
