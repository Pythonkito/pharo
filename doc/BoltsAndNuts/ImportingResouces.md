# Importing Resources

The key point to understand is that we need to encode binary on string (that we want to store in method body). So we have to change the representation going back and forth between binary and string.

Consider the following example:


```
It takes less space in the image

```


```

Here we compile two methods: `imageSource` which returns 
an encoded image and `image` which returns the PNG from the encoded string. 

```


```