# HW8-Web-Servers

Our web server contains 2 images **/web/1.jpg** and **/web/2.jpg**


Step 1: access this images 2 times to triger cache

![Step 1](https://gcdnb.pbrd.co/images/lU3psObLz77o.png?o=1)

Step 2: replace images with images from **/web/img_set_2** folder

Step 3: check that we recieve old http://localhost:8000/1.jpg and old http://localhost:8000/2.jpg

![Step 1](https://gcdnb.pbrd.co/images/lU3psObLz77o.png?o=1)

Step 4: call cache bypass for 1.jpg by caling http://localhost:8000/1.jpg?nocache=1

Step 5: check that we recieve new http://localhost:8000/1.jpg and old http://localhost:8000/2.jpg

![Step 5](https://gcdnb.pbrd.co/images/a2ZtijgzZ77H.png?o=1)

Step 6: call cache bypass for 2.jpg by caling http://localhost:8000/2.jpg?nocache=1

Step 7: check that we recieve new http://localhost:8000/1.jpg and new http://localhost:8000/2.jpg

![Step 7](https://gcdnb.pbrd.co/images/dOToig1Zjl5y.png?o=1)
