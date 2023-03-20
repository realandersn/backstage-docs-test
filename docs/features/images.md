# Images

!!! note
    You cannot link to images outside of the root `/docs` folder. This is a Mkdocs limitation. You can move images to inside the `/docs` folder and use them inside of TechDocs as usual.

Link to images in an img folder using a relative path, using forward slash.
Make sure your img folder is placed inside the 'docs' folder.

<pre>
![image](./img/image4.png)
</pre>

!!! tip
    You can resize your images through the use of the [attr_list](https://python-markdown.github.io/extensions/attr_list/) plugin, using the following syntax:
    
    `![image](./img/image4.png){: style="height:150px;width:150px"}`
