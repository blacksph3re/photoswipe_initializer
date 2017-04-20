A javascript initializer for the photoswipe js library. Depends on JQuery and Photoswipe

# Usage
Ćreate a div somewhere on the page and add the following script after loading jquery:

´´´
<script>
  
var items = [
  {
    src: 'path/to/image.jpg',
    w: 100,
    h: 100,
    title: 'Some title'
  }
];
initGallery($('#your_div_id'), items);

</script>
´´´