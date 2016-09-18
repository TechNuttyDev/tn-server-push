# HTTP2 SERVER PUSH #

Here's the code that you'll need to add multiple files to a HTTP/2 Server Push setup on Apache. Just add it to your .htaccess file and change the links and you are ready.

```
 Header append Link: "</TechNuttyLogo.svg>; rel=preload; as=image"

 Header append Link: "</TechNuttyLogo.png>; rel=preload; as=image"

 Header append Link: "(you get the point :)"
 ```

Just make sure to change the as tag to the link that you are adding, there's:

image

script

style

media
