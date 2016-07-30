# Bootstrap TouchSpin [![Build Status](https://secure.travis-ci.org/istvan-ujjmeszaros/bootstrap-touchspin.png?branch=master)](https://travis-ci.org/istvan-ujjmeszaros/bootstrap-touchspin)

##### Bootstrap TouchSpin is a mobile and touch friendly input spinner component for Bootstrap 3.

- [Website](http://www.virtuosoft.eu/code/bootstrap-touchspin/)

Please report issues and feel free to make feature suggestions as well.

## FuckDoctors's Customize
- add `useBootstrap` option, which is `true` by default.
  - `true` : use bootstrap themes, with `form-control`, `input-group-addon` features
  - `false` : with no `form-control`, `input-group-addon`, therefore, you can set spinner's up and down button by youself

## FuckDoctors's Customize usage
```
$("input[class='count']").TouchSpin({
	initval: 0,
	min:0,
	max:100,
	useBootstrap: false, // to active custimze mode
	buttondown_class:'spinner-down', // your own spinner down button's css
	buttonup_class:'spinner-up', // your own spinner up button's css
	buttonup_txt:'<img src="images/add.png" />', // change '+' to image
	buttondown_txt:'<img src="images/cut.png" />' // change '-' to image
});
```
Here is the example:

![image](./demo/customize/example.png)

## License

Apache License, Version 2.0

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/73ffb6b38e5099909d7b13c577d7e5c8 "githalytics.com")](http://githalytics.com/istvan-ujjmeszaros/bootstrap-touchspin)
