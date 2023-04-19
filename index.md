# Learning GitHub

Can be fun. It surely is. It still takes time though.

## Markdown

I know this already. I use it everyday. 

![GitHub logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### Translate any WP string

Place the code below in your child theme's *function.php* file:

```
add_action( 'wp_enqueue_scripts', 'child_enqueue_styles', 15 );

function my_text_strings( $translated_text, $text, $domain ) {
    switch ( $translated_text ) {
        case 'Or' :
            $translated_text = __( 'Lub' );
            break;
    }

    return $translated_text;
}
add_filter( 'gettext', 'my_text_strings', 999, 3 );
```
### Task list

My activities in this course
- [x] Add headers
- [x] Add an image
- [x] Add a code example
- [x] Make a task list
- [ ] Merge your pull request
