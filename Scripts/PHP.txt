/* HEADER CODE FOR FAVICON */
add_action('wp_head', 'favicon');
function favicon(){
?>
<link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">
<link rel="icon" href="/favicon.ico" type="image/x-icon">
<?php
};

