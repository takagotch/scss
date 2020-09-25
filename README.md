### sass
---
http://sass-lang.com/documentation/file.SASS_REFERENCE.html


https://github.com/takagotch/page351/blob/master/src/styles/README.md

centos8
```.sh
yum list installed | grep ruby
yum list installed | grep ruby-devel
yum list installed | grep rubygems
yum list installed | grep gcc
sudo yum install ruby
sudo yum -y install ruby-devel
sudo yum install rubygems
sudo yum install gcc

sudo gem install compass
sudo gem install sass
sass -v
compass -v
compass watch


```

ubuntu
```.sh
sudo apt-get install ruby
sudo su -c "gem install sass"



```

---

https://www.npmjs.com/package/gulp-sass
https://www.npmjs.com/package/gulp-sass-glob
https://github.com/twbs/bootstrap-sass

####### responsive
* large<br>
801px~
* midium<br>
601~801px
* small<br>
~600px

###### media query
large > midium > small

/* large css */
@media(max-width: 800px){
  /* medium css */
  .c-disp{display: block;}
}

@media(max-width: 600px){
  /* small css */
  .c-disp{display: none;}
}

/* Mixin */
@include max-screen($BREAK_PORINT_MD){
  /* medium css */
  .c-disp{display: block;}
}
@include max-screen($BREAK_POINT_SM){
  /* small css */
  .c-disp{display: none;}
}

###### viewport
<meta name="viewport" content="widht=device=width, initial-scale=1">

[![scss](http://localhost:3000/)] []

** **

```


```

- 
  -
