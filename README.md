# snazzymaps
JSON for all Snazzy Maps styles
up to style/56252/1 by Bast

Recommended use for development only
Example usage with Google Maps API v3

<script type='text/javascript' src='styles.js'></script>

var myOptions = {
  ...
  styles: styles['pale-dawn']
};
var map = new google.maps.Map(document.getElementById('map'), myOptions);
