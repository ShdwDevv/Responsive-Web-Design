# Responsive-Web-Design
![alt text](./images/screenshot/image.png)
![alt text](./images/screenshot/image-1.png)
![alt text](./images/screenshot/image-2.png)
![alt text](./images/screenshot/image-3.png)
![alt text](./images/screenshot/image-4.png)
![alt text](./images/screenshot/image-5.png)
![alt text](./images/screenshot/image-6.png)
![alt text](./images/screenshot/image-7.png)
![alt text](./images/screenshot/image-8.png)
* 1em = match the font size of the family (100 %)
* 1.5 em = 150% of parent 
![alt text](./images/screenshot/image-9.png)
eg. 1.5 * 1.5 * 1.5 massive issue
* So the solution for this is `rems`
![alt text](./images/screenshot/image-10.png)
![alt text](./images/screenshot/image-11.png)
![alt text](./images/screenshot/image-12.png)
* Apart from font size(relative to parent) , em is relative to own element's font size(padding,margin)
![alt text](./images/screenshot/image-13.png)
* The above problem is solved by give the value of the padding of the button in `em`
![alt text](./images/screenshot/image-14.png)
## Responsive Layout Basics
![alt text](./images/screenshot/image-15.png)
![alt text](./images/screenshot/image-16.png)
![alt text](./images/screenshot/image-17.png)
![alt text](./images/screenshot/image-18.png)
* Try to put image as `max-width:100%;`
* Compound selector - A compound selector in CSS is used to combine multiple selectors to apply specific styles to elements that match all the criteria of the combined selectors. It allows you to target elements based on more than one condition, making your styling more precise and targeted.
## Media query
![alt text](./images/screenshot/image-19.png)
![alt text](./images/screenshot/image-20.png)
![alt text](./images/screenshot/image-21.png)
![alt text](./images/screenshot/image-22.png)
![alt text](./images/screenshot/image-23.png)
![alt text](./images/screenshot/image-24.png)
![alt text](./images/screenshot/image-25.png)
![alt text](./images/screenshot/image-26.png)
![alt text](./images/screenshot/image-28.png)
![alt text](./images/screenshot/image-27.png)
* Atleast 400px need to be there
![alt text](./images/screenshot/image-29.png)
* Always orders matters
![alt text](./images/screenshot/image-30.png)
* The above never get orange
* After flex-direction : column
![alt text](./images/screenshot/image-31.png)
![alt text](./images/screenshot/image-32.png)
![alt text](./images/screenshot/image-33.png)
![alt text](./images/screenshot/image-34.png)
![alt text](./images/screenshot/image-35.png)
* We are going to do this
![alt text](./images/screenshot/image-36.png)
![alt text](./images/screenshot/image-37.png)

* All Device Layout [click here](https://xd.adobe.com/spec/75d448ea-569a-4b7e-721b-9bbd3b2b97b9-03e5/grid/)
* Bold vs bolder
    * bold -> 300 to 700
    * bolder -> 300 to 400
* In media Start to think for mobie 
* So first remove the mdia query and add them in normal class
![alt text](./images/screenshot/image-38.png)
![alt text](./images/screenshot/image-39.png)
![alt text](./images/screenshot/image-40.png)