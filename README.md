# Responsive-Portfolio

The objective of this project was to create a responsive portfolio on a web page and to design the page using css elements from the bootstrap library. Another element of this project was changing the css stylings of html elements to make the page scale better to different window sizing viewing the page.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

For all users the first thing you are going to need is to install git. If you already have git installed and have configured your account onto your local machine, then skip the following steps and go to the installing section. You can find the instructions on how to download and install the git software for  operating systems of Linux, Mac and Windows at the following link: 
[Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

<br>
Once you are on the page select the corresponding download link to the operating system of your own machine and follow the instructions.
<br>
After having installed the software and have created your own github account, you will now have to link your account to your local machine and you can do this by following the instructions at this link:  

<a href ="https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent" >SSH Key</a>


### Installing

Now that you have git installed and you have configured your account to your local machine your next step will be to click on the clone or download button on the page of this repository and click on the clipboard symbol to copy the link. Next open up terminal (mac) or bash (windows), navigate to the directory you want your cloned directory to reside at, and type in the following code:

```
git clone
```

Then paste the copied link.

```
git clone git@github.com:RoyceWilliams510/code-refactor.git
```

Now you will have the cloned directory on your local machine and you can open it up with vscode or any other text editor to examine and edit it's contents.

## How to use the directory
When you open the contents of this repository, one of the first things you will notice is the fact that there are 3 html files. Each of these files actually correspond to a different part of the portfolio and can be found in the links provided in the nav bar on the top of the page.

<br>
For the About me page that will correspond to the index.html file, the portfolio.html file of course corresponds to the portfolio page, and the contact.html file corresponds to the contact page.

<br>
If you open the assets directory you can find a folder labeled images, which holds the images for the intended structures of the three pages on three different window scalings of 640px 768px and 980px. Also in the Assets directory are three different css files that all link to the three different html files to assist in the scaling of the page. The way that these css files aid in scaling is through this line of code: 

```
@media screen and (max-width: 640px) {

}
```
This line of code helps adjust properties of elements when the window viewing the page is a certain size.

## Built With
* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)


## Deployed Link

* [See Live Site](https://roycewilliams510.github.io/code-refactor/index.html)


## Authors

 **Royce Williams** 

- [Github](https://github.com/RoyceWilliams510/)
- [LinkedIn](https://www.linkedin.com/in/royce-williams-3334261ab/)

## License

This project is licensed under the Bootstrap License 
