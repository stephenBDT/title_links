## Title Links

In some cases, we need hide the standard name of a DocType in favor of another value in the doctype, 
and get it simple to the end user.

Title Links, do exactly it, it replace the value displayed in the **Links** and **Dynamic Links** fields, 
to the value of the title field, defined in your **DocTypes**.

When the title is not present, we will ensure the same behavior of the original widgets of frappe, displaying 
the name.

That is how the normal behavior of Link Widget looks like:

<img width="455" alt="schermata 2017-02-08 alle 13 31 23" src="https://cloud.githubusercontent.com/assets/11652845/22737344/fba13bb2-ee02-11e6-9c54-dd8a0e20d3d4.png">

This is how the related record looks like in frappe

<img width="1216" alt="schermata 2017-02-08 alle 12 49 27" src="https://cloud.githubusercontent.com/assets/11652845/22736142/1abc4e8e-edfd-11e6-92b8-78ad41242f43.png">

Frappe, already replace the title value in the visualization area of the Form, and show the original name, in the right side of the form, as a small text.
Why we can't do the same to the links?

To me it's by designe is not enought, so I decided to hack frappe.

After install this app, and configure the DocTypes that you need to change to title, like the below image, 

<img width="1209" alt="schermata 2017-02-08 alle 12 34 19" src="https://cloud.githubusercontent.com/assets/11652845/22735737/54096ca0-edfb-11e6-9746-9cbbf9f0aa9d.png">

Your links will look like

<img width="460" alt="schermata 2017-02-08 alle 17 00 56" src="https://cloud.githubusercontent.com/assets/11652845/22747130/6967474a-ee26-11e6-9231-5ccaeb1dc904.png">


#### License

MIT