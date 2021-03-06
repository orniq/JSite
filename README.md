# JSite - Website software based on pure HTML, CSS, JavaScript and JSON
This is the website code based on pure HTML,CSS, JavaScript and JSON. This code is useful for developing websites who write tutorials, articles, documentation. Simple configuration steps to setup the site and easy to write articles/tutorials for your website. 

![alt HTML, CSS, JavaScript, JSON](https://img.shields.io/badge/Technologies-HTML,%20CSS,%20JavaScript,%20JSON-deeppink?style=for-the-badge) ![alt Vesrion 0.1](https://img.shields.io/badge/Version-0.1-green?style=for-the-badge)

# JSite Logo
![alt JSite Logo](https://drive.google.com/uc?id=1wMImMV9X9bxzEW3s18H716W3_ImShwQc&export=download)
## Alternative Logo
![alt JSite Logo](https://drive.google.com/uc?id=1WQo5FDiLfUyPoz89eLwqYpEFL3IvWD8A&export=download)


##### Color Codes of JSite Logo: White , #000000 (Black)  and #f6bb25 (Orange) 
#### Font Style of Jsite: Barlo Black
#### Letter Space : 99
#### Ltter J font size: 150
#### The word Site font size : 118
#### The word Website software font size: 25
#### Base width of the logo 500px ( based on these width the above units mentioned )

# JSite Sample Page
![alt Home Page of Jsite](https://drive.google.com/uc?id=1LimXSW54PTOtfxcWhWNXNIs6ldr2OaMk)

# Home Page of Jsite
![alt Home Page of Jsite](https://drive.google.com/uc?id=1tGtYqV7jUVXkgOl1t10PTd9XnwZh7nPO)
# Article/Tutotials Full View Page 
![alt Home Page of Jsite](https://drive.google.com/uc?id=1JKGSFYPGueScVzW1n1jxlsViNmBc6m3K)
# Code Block in Article/Tutotials Full View Page 
![alt Home Page of Jsite](https://drive.google.com/uc?id=1C1F7ZQPMX9bQil1J7BBfllA9ZRFG7nfd)
# Mobile View of Home Page
![alt Home Page of Jsite](https://drive.google.com/uc?id=1Ighk3XZUneYXLZKBdsFmK5LGH1hh6Nmu)
# How to write Articles
### images auto caption and lazy loading

```HTML
<figure class="figure">
    <img class="lazy" data-src="https://source.unsplash.com/random/642" />
    <figcaption>Image Caption Here</figcaption>
  </figure>
 ```
 
 #### images with preloader when using lazy loading concept
 ```HTML
  <figure class="figure">
    <img class="lazy" src="images/image-pre-loader.gif" data-src="https://drive.google.com/uc?id=1tGtYqV7jUVXkgOl1t10PTd9XnwZh7nPO&export=download" />
    <figcaption>Home Page of JSite</figcaption>
  </figure>
```
#### image in the right side of the content
```HTML
  <figure class="figure figure-right">
    <img class="lazy" src="images/image-pre-loader.gif" data-src="https://drive.google.com/uc?id=1wMImMV9X9bxzEW3s18H716W3_ImShwQc" />
    <figcaption>JSite Logo</figcaption>
  </figure>
```

#### image in the left side the contnet
```HTML
  <figure class="figure figure-right">
    <img class="lazy" src="images/image-pre-loader.gif" data-src="https://drive.google.com/uc?id=1wMImMV9X9bxzEW3s18H716W3_ImShwQc" />
    <figcaption>JSite Logo</figcaption>
  </figure>
```


 ### Code Blocks in Article
 Following is the snippet to add code from github repositories into article full view
 ```HTML
  <div class="codeBlock" owner="jai43" repo="spring-example-snippets" ref="master" embeded='{"path": "springBoot/@Bean/singleton_bean.java" },{"path": "springBoot/@Bean/prototye_bean.java" }' style="height:600px;"></div>
```
- **owner** attribute holds the owner of github reposiotry.
- **rep** attribute holds the name of github repository from which code to be displayed.
- **ref** attribute holds the branch name 
- **path** holds the path of the code file to be displayed in codeblock
#### example code block
[Click Here to see sample code block](#code-block-in-articletutotials-full-view-page)




  
  

