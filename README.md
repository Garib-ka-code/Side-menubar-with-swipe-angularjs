Add two file into your repo : materialize.js and materialize.css


HTML Structure :

Checkout index.html page

Controller part:

    // start menu bar //
    $('.drag-menu').sideNav({
          menuWidth: 300, // Default is 240
          edge: 'left', // Choose the horizontal origin
          closeOnClick: true // Closes side-nav on <a> clicks, useful for Angular/Meteor
        }
    );
    $('body').css('overflow', 'visible');
    $('#sidenav-overlay').remove();
    // End menu bar //
