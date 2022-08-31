# Gautam Sagar Mallela
###### The British Museum

I am so exhited to see **Dinosaur fossils** and many ancient and **historic sculptures**.

---

# Directions to Museum

1. After coming out from the airport walk towards NW Roanridge road.
2. Walk 100 meters towards north.
3. you can find a sign board on the right side which is attached to a road, which will directly take you to the Museum.


# Other interesting locations

* waterfall
* parks
* trekking



**[AboutMe](AboutMe.md)**

---

# Recommended Cities 

I am recommending few city and places within that city which are famous and even mentioned how much time you need to spend at each loaction.


| Name | Location in City | Time to spend |
|:-----|:-----------------|--------------:|
| Hyderabad | Charminar   |  2 hrs        |
| Warangal  | Thousand pillars | 3 hrs    | 
| Tirupati  | Tirumala Temple  |  1 day   | 
| Hyderabad | Birla Temple     | 4 hrs    |

---

# Quotes

> “There are two ways of spreading light: to be the candle or the mirror that reflects it.”  – *Edith Wharton*

> “You do not find the happy life. You make it.” – *Camilla Eyring Kimball*

---

# Code Fencing

# wordpress

> function my_enqueue($hook) {
    if( 'edit.php' != $hook )
        return;
    wp_enqueue_script( 'my_custom_script', plugins_url('/myscript.js', __FILE__) );
}
add_action( 'admin_enqueue_scripts', 'my_enqueue' );
>> function load_custom_wp_admin_style() {
        wp_register_style( 'custom_wp_admin_css', get_template_directory_uri() . '/admin-style.css', false, '1.0.0' );
        wp_enqueue_style( 'custom_wp_admin_css' );
}
add_action( 'admin_enqueue_scripts', 'load_custom_wp_admin_style' );

stackoverflow page: <https://stackoverflow.com/questions/18553610/how-do-i-add-custom-css-and-js-files-to-admin-area-of-wordpress>

# css tricks

```
add_action('admin_head', 'my_custom_fonts');

function my_custom_fonts() {
  echo '<style>
    body, td, textarea, input, select {
      font-family: "Lucida Grande";
      font-size: 12px;
    } 
  </style>';
}
```
css-tricks page: <https://css-tricks.com/snippets/wordpress/apply-custom-css-to-admin-area/>

