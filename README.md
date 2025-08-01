bash-bmp
========

Generate Bitmap data in pure bash.

<!--TODO: Watch how it was made on [YouTube](..url..).-->

Usage
-----

Simple BMP (2x2 pixels)

    ./simple-bmp > out.bmp

![simple-bmp](https://files.daveeddy.com/ysap/bmp/simple.png)

Color Gradient

    ./gradient -h 200 -v 200 -o out.bmp

![gradient](https://files.daveeddy.com/ysap/bmp/gradient.png)

    cat smile.txt | ./sprite-to-bmp -p palette.txt -o out.bmp

![smile](https://files.daveeddy.com/ysap/bmp/smile.png)

License
-------

- MIT License

<!--
YouTube
-------

<a href="https://www.youtube.com/watch?v=L967hYylZuc"><img alt="Bash Webserver YouTube
Thumbnail" src="https://files.daveeddy.com/ysap/bash-webserver-thumbnail.jpg"
/></a>

-->
