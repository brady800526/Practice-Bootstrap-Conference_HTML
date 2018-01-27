## Summary

The code in this repo follows the teacher in Treehouse. By using BootStrap framework, we could easily make a website without any Javascript code.

*All the step is followed by [Bootstrap 4 Course](https://teamtreehouse.com/library/flask-basics) created by Guil Hernandez.*

## Bootstrap

Bootstrap is a web framework that can rapidly build a website without any JavaScript code. The benefit of this framework is, if you are selling pure web design, using it to build super fast because you can use Bootstrap CDN help you accomplish JavaScript function. 
On the contrary, it might look very similar with other website also using this. Using custom.css yourself to redisign or override the css attribute may help you out.

## Usage

Download the repo, under the directory run:

    open index.html

You will see the landing page.

<figure style="text-align: center;">
    <img src="http://i66.tinypic.com/3444nk1.png" alt="Landing Page" style="width: 49.5%; height: 49.5%"/>
    <img src="http://i65.tinypic.com/2ic1tvt.png" alt="Landing Page" style="width: 49.5%; height: 49.5%"/>
    <figcaption style="display: block;">Landing Page</figcaption>
</figure>

This website is assumed to be used for JavaScript conference, the components of this conference includes About, Speakers, Schedules and Register Form.

After you click the Register Now button, register from will show up to ask you fill in your personal info.

<figure style="text-align: center;">
    <img src="http://i66.tinypic.com/jk9l5w.png" alt="Register Form" style="width: 40%; height: 40%"/>
    <figcaption style="display: block;">Register Form</figcaption>
</figure>

However, we didn't process any data after Register button is pressed.

## Code

Here, we only separately list the components used in this project since it just copy from the Bootstrap website and everything works like charm! Amazing! You can see more detail in [Bootstrap components](https://getbootstrap.com/docs/4.0/components/alerts/).

#### [Getting Started](https://getbootstrap.com/docs/4.0/getting-started/introduction/) - Render all stuff from CDN
------------------------------------------------------------------------

index.html

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
```

This is the [starter template](https://getbootstrap.com/docs/4.0/getting-started/introduction/), just copy the code here to your html in order to render the Bootstrap CDN and jQuery package.

### [Navs](https://getbootstrap.com/docs/4.0/components/navs/) - Show the nav
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i68.tinypic.com/2dtx0gh.png" alt="Navs" style="width: 100%; height: 100%"/>
</figure>

```
<ul class="nav">
  <li class="nav-item">
    <a class="nav-link active" href="#">Active</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled" href="#">Disabled</a>
  </li>
</ul>
```

### [Navbar](https://getbootstrap.com/docs/4.0/components/navbar/) - Show the nav bar
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i65.tinypic.com/k2xpus.png" alt="Nav bar" style="width: 100%; height: 100%"/>
</figure>

```
<nav class="navbar navbar-light bg-light justify-content-between">
  <a class="navbar-brand">Navbar</a>
  <form class="form-inline">
    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
  </form>
</nav>
```

### [Jumbotron](https://getbootstrap.com/docs/4.0/components/jumbotron/) - Large scene to show
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i63.tinypic.com/2vvuixt.png" alt="Jumbotron" style="width: 100%; height: 100%"/>
</figure>

```
<div class="jumbotron">
  <h1 class="display-4">Hello, world!</h1>
  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
  <hr class="my-4">
  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
  <p class="lead">
    <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
  </p>
</div>
```

### [Button group](https://getbootstrap.com/docs/4.0/components/button-group/) - Group all the buttons together
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i66.tinypic.com/14t5y0h.png" alt="Button group" style="width: 100%; height: 100%"/>
</figure>

```
<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-secondary">Left</button>
  <button type="button" class="btn btn-secondary">Middle</button>
  <button type="button" class="btn btn-secondary">Right</button>
</div>
```

### [Cards](https://getbootstrap.com/docs/4.0/components/card/) - Show individuals in templates theme
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i66.tinypic.com/11ay045.png" alt="Cards" style="width: 100%; height: 100%"/>
</figure>

```
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="..." alt="Card image cap">
  <div class="card-body">
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
</div>
```

### [List group](https://getbootstrap.com/docs/4.0/components/list-group/) - Show all the info in a list form
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i65.tinypic.com/fuqb8z.png" alt="RList group" style="width: 100%; height: 100%"/>
</figure>

```
<ul class="list-group">
  <li class="list-group-item d-flex justify-content-between align-items-center">
    Cras justo odio
    <span class="badge badge-primary badge-pill">14</span>
  </li>
  <li class="list-group-item d-flex justify-content-between align-items-center">
    Dapibus ac facilisis in
    <span class="badge badge-primary badge-pill">2</span>
  </li>
  <li class="list-group-item d-flex justify-content-between align-items-center">
    Morbi leo risus
    <span class="badge badge-primary badge-pill">1</span>
  </li>
</ul>
```

### [Scrollspy](https://getbootstrap.com/docs/4.0/components/scrollspy/) - Target the html id when scrolling with active effect
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i68.tinypic.com/974c4k.png" alt="Scrollspy" style="width: 100%; height: 100%"/>
</figure>

```
<nav id="navbar-example2" class="navbar navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <ul class="nav nav-pills">
    <li class="nav-item">
      <a class="nav-link" href="#fat">@fat</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#mdo">@mdo</a>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false">Dropdown</a>
      <div class="dropdown-menu">
        <a class="dropdown-item" href="#one">one</a>
        <a class="dropdown-item" href="#two">two</a>
        <div role="separator" class="dropdown-divider"></div>
        <a class="dropdown-item" href="#three">three</a>
      </div>
    </li>
  </ul>
</nav>
<div data-spy="scroll" data-target="#navbar-example2" data-offset="0">
  <h4 id="fat">@fat</h4>
  <p>...</p>
  <h4 id="mdo">@mdo</h4>
  <p>...</p>
  <h4 id="one">one</h4>
  <p>...</p>
  <h4 id="two">two</h4>
  <p>...</p>
  <h4 id="three">three</h4>
  <p>...</p>
</div>
```

### [Dropdowns](https://getbootstrap.com/docs/4.0/components/dropdowns/) - Show the dropdowns
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i65.tinypic.com/jg0dx2.png" alt="Dropdowns" style="width: 100%; height: 100%"/>
</figure>

```
<div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Dropdown button
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
  </div>
</div>
```

### [Modal](https://getbootstrap.com/docs/4.0/components/modal/) - Popup a modal on the current scene
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i68.tinypic.com/27x17ax.png" alt="Modal" style="width: 100%; height: 100%"/>
</figure>

```
<div class="modal" tabindex="-1" role="dialog">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Modal body text goes here.</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-primary">Save changes</button>
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
```

### [Forms](https://getbootstrap.com/docs/4.0/components/forms/) - Show a form to register or write in
------------------------------------------------------------------------

<figure style="text-align: center;">
    <img src="http://i66.tinypic.com/20seyps.png" alt="Forms" style="width: 100%; height: 100%"/>
</figure>

```
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```


## Conclusion

In this project, we almost use all the componetns to build the website. Besdies, there are also a lot of typography and utilities used in this project. But those things are very subtle and tedious, I think that could be surveyed after familiar with all the components here.
