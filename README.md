# Django filter_horizontal(filter_vertical) search bar both sides

Django filter_vertical(filter_horizontal) improvement. Enables search for both available and chosen boxes in filter_vertical(filter_horizontal) fields

In file SelectFilter2.js added a second filter for the selected positions. Corrected the file SelectBox.js to properly interact with the new filter. 

Replace in your static/admin/js/SelectFilter2.js and static/admin/js/SelectBox.js

To resize the widget filter vertically, copy the file resize_widget_filter_vertical.css  and paste it into your project
(static/admin/css/resize_widget_filter_vertical.css)

### Filter Display Examples

[![filter-vertical.jpg](https://i.postimg.cc/DZZLyhBH/filter-vertical.jpg)](https://postimg.cc/06TbcTg0)


[![filter-horizontal.jpg](https://i.postimg.cc/Y2xBwwJM/filter-horizontal.jpg)](https://postimg.cc/RqqDc2SD)
