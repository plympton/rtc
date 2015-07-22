# Recovering the Classics

Canonical source of books, covers and images.

## Use

Books.json contains a list of book objects.
Each book object contains `name` and `author` and a list of `covers`.
Each cover object contains a `filename` and an `artist`.

The filenames are relative, since there has been no canonical place to host cover images.
However, they can be served through [rawgit](http://rawgit.com) using the following scheme in your app:

`https://cdn.rawgit.com/plympton/rtc/master/rtc_books/{filename.jpeg}`

Smaller, 400px versions are available at:

`https://cdn.rawgit.com/plympton/rtc/master/rtc_books_resized/{filename.jpeg}`

In the future, we hope to have more image sizes available or serve images through a cdn that provides on-demand image optimization.

## Future

Future books and covers will be added to the repo periodically. Follow the commit logs for more.

## License

Book covers are licensed for non-commercial use, with attribution, only (see [LICENSE.md](license.md)). For commercial licensing, please send an email to hello@recoveringtheclassics.com.

## More Info
http://recoveringtheclassics.com

http://50x50.us
