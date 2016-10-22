# GrabMoonCake
Fake page GrabMoonCake.html that grabing moon cake.
#Usages
##1 load GrabMoonCake page
![Chrom Page](http://i.imgur.com/KGsZzcX.jpg)
##2 Option1
###2.1 Development Model, ctrl+shift+I
![console ](http://i.imgur.com/81IkCuc.jpg)
###2.2 insert setInterval function in console
setInterval(function(){
		$("#rush").trigger('click')
	}, 1000)
![insert](http://i.imgur.com/syUrZVF.jpg)

you can see that every 1 second, print one logs.
##2 Option2
###2.1 put the grab script as chrom extension
setInterval(function(){
		$("#rush").trigger('click')
	}, 1000)
save as user.js as suffix, for example, test.user.js, and click chrome://extensions/, drag test.user.js to this extensions and reload chrom, load GrabMoonCake.html page, also you can the same case as option1.
