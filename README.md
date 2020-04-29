# Scss-Responsive
## This is my scss responsive file.

## Usage
```
//import my file in your scss file

@import '../node_modules/scss-responsive-by-hkz/css/responsive.scss';


//Use my code for small-device

@include screen(small-device){

//anything you want to change in small devices

}


//Use my code for mobile

@include screen(mobile){

//anything you want to change in mobile

}


//Use my code for tablet

@include screen(tablet){

//anything you want to change in tablet

}




//Use my code for laptop

@include screen(laptop){

//anything you want to change in laptop

}


//Use my code for desktop

@include screen(desktop){

//anything you want to change in desktop

}

```

## You can also use multiple screen like this:
```
//Use my code for multiple screen

@include screen(small-device mobile tablet laptop desktop){

//anything you want to change in multiple screen

}

