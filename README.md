jQuery - toTop()
=======
A simple, highly customizable and ultra light-weight (~1KB) plugin for smoothly Scroll back to Top.

------
[View Demo](http://mmkjony.github.io/jQuery.toTop/)

### How to Use:
------
**1. At first include [jQuery](http://jquery.com/download/) and jquery.toTop.js**
````html
  <script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
  <script src="jquery.toTop.min.js"></script>
````

**2. Include HTML**
````html
  <a class="to-top">Top &uarr;</a>
````
You can add any html element, and style it as you want

**3. Activate the Plugin**
````javascript
  $('.to-top').toTop();
````

### Options:
------

| Option        | Value           | Desciption  |
| :------------- |:-------------| :-----|
| autohide | boolean | You have options whether you want your button to hide automatically or not. You can choose 'true' or 'false'. `default: true` |
| offset | Integer (px) | Scrolling length from top to hide automatically. `default: 420` |
| speed | Integer (ms) | The duration for scroll and fade speed. `default: 500` |
| position | boolean | You have this option whether you want to add custom position in css. Set this 'false' if you want to add custom position with your own css. `default: true` |
| right | Integer (px) | Position from right. (It will work only if 'position' is set 'true'.) `default: 15` |
| bottom | Integer (px) | Position from bottom. (It will work only if 'position' is set 'true'.) `default: 30` |


### Plugin activation with options

````javascript
  $('.to-top').toTop({
      //options with default values
      autohide: true,
      offset: 420,
      speed: 500,
      position: true,
      right: 15,
      bottom: 30
  });
````


### Changelog:
------
**v1.1**

* Options added for custom positioning.

**v1.0**

* Initial Release


### License
------
This plugin is licensed under [MIT](LICENSE)
