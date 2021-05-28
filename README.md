# lamestuff.com 2007

This is my personal website (lamestuff.com) as it was built in January of 2007.

I built it in PHP with a special structure inspired by some of the stuff I'd learned about in Rails.

to make this work, all requests should be directed to the `index.php` file using Apache config. It also has a
built-in counter (`counter.dat`) file that gets incremented with every request to the homepage, I believe.

This app doesn't use any kind of relational database and relies on conventions in the file structure to piece
together the pages and the copy on this served as a basis for my rewrite of the site in 2009 when it was
ported to Rails.
