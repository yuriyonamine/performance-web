#Implementation of web performance techniques

* Minify files (js, css, html) -> removes comments, spaces, and others to reduce the file size. (Be careful when removing spaces from html file. It may affect the final result, e.g., in `<pre>` tag). This is used in deployment enviroment.

* Turn on GZIP in your WebServer in order to compress your files before sending to the user's browser. Some servers, by default, compress only HTML files. Therefore, you will probably need to configure the other file types.
