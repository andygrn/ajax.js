ajax.js
=======

ajax.js is a super-simple, 1kb, wait for it, ajax utility.

### Size

* Source: 2.3kb
* Minified: 1kb
* Gzipped: 628 bytes


### Usage

The API is very similar to that of jQuery's ajax method. You should
immediately feel at home.

    ajax({
      type: 'get',
      url: 'http://example.com',
      data: {name: 'John Smith'},
      timeout: 5000,
      headers: [
        ['X-Custom-Header', 'Header-Content'],
        ['X-Custom-Header-2', 'Header-Content']
      ],
      onSuccess: function(data) {
        console.log('Here is the data: ' + data);
      },
      onComplete: function() {

      },
      onError: function() {

      }
    });

