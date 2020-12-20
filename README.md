# Bootstrap Cheatsheet 1.0.0

## Made for the Bootstrap crash course by **[SecTheater](https://www.youtube.com/c/SecTheater?sub_confirmation=1)** community, if you would like to watch it [click here](https://www.youtube.com/c/SecTheater?sub_confirmation=1)

---

|                 Table                  |                  of                  |                      contents                      |
| :------------------------------------: | :----------------------------------: | :------------------------------------------------: |
|    [Navbar](#Navbars-in-bootstrap)     |    [Badges](#Badges-in-bootstrap)    |      [Positioning](#Positioning-in-bootstrap)      |
|     [Alerts](#Alerts-in-bootstrap)     |    [Tables](#Tables-in-bootstrap)    | [Button modifiers](#Button-modifiers-in-bootstrap) |
|    [Buttons](#Buttons-in-bootstrap)    |    [Modals](#Modals-in-bootstrap)    |    [Button groups](#Button-groups-in-bootstrap)    |
|      [Grids](#Grids-in-bootstrap)      |      [Navs](#Navs-in-bootstrap)      |            [Forms](#Forms-in-bootstrap)            |
|     [Images](#Images-in-bootstrap)     |     [Texts](#Texts-in-bootstrap)     |         [Displays](#Displays-in-bootstrap)         |
| [Jumbotrons](#Jumbotrons-in-bootstrap) |    [Colors](#Colors-in-bootstrap)    |       [Pagination](#Pagination-in-bootstrap)       |
|      [Lists](#Lists-in-bootstrap)      | [Dropdowns](#Dropdowns-in-bootstrap) | [Form input group](#Form-input-group-in-bootstrap) |
|      [Cards](#Cards-in-bootstrap)      |   [Borders](#Borders-in-bootstrap)   |           [Toasts](#Toasts-in-bootstrap)           |
| [Accordions](#Accordions-in-bootstrap) |   [Spacing](#Spacing-in-bootstrap)   |                -------------------                 |
|   [Spinners](#Spinners-in-bootstrap)   |    [Sizing](#Sizing-in-bootstrap)    |                -------------------                 |

# Navbars in bootstrap

Navbar with almost everything, search bar, drop down menu

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarSupportedContent"
    aria-controls="navbarSupportedContent"
    aria-expanded="false"
    aria-label="Toggle navigation"
  >
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#"
          >Home <span class="sr-only">(current)</span></a
        >
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item dropdown">
        <a
          class="nav-link dropdown-toggle"
          href="#"
          id="navbarDropdown"
          role="button"
          data-toggle="dropdown"
          aria-haspopup="true"
          aria-expanded="false"
        >
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input
        class="form-control mr-sm-2"
        type="search"
        placeholder="Search"
        aria-label="Search"
      />
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">
        Search
      </button>
    </form>
  </div>
</nav>
```

Coloured navbars

```html
<!-- Dark navbar -->
<nav class="navbar navbar-dark bg-dark">
  <!-- Navbar content -->
</nav>

<!-- Blueish bluenavbar -->
<nav class="navbar navbar-dark bg-primary">
  <!-- Navbar content -->
</nav>

<!-- light-blue bluenavbar -->
<nav class="navbar navbar-light" style="background-color: #e3f2fd;">
  <!-- Navbar content -->
</nav>
```

# Alerts in bootstrap

```html
<div class="alert alert-primary" role="alert">
  <strong>Well done!</strong> You successfully read this important alert
  message.
</div>
```

```html
<div class="alert alert-secondary" role="alert">
  <strong>Well done!</strong> You successfully read this important alert
  message.
</div>
```

```html
<div class="alert alert-success" role="alert">
  <strong>Well done!</strong> You successfully read this important alert
  message.
</div>
```

<link
    rel="stylesheet"
    href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
    crossorigin="anonymous"
/>
<div class="alert alert-info" role="alert">
  <strong>Heads up!</strong> This alert needs your attention, but it's not super
  important.
</div>

```html
<div class="alert alert-info" role="alert">
  <strong>Heads up!</strong> This alert needs your attention, but it's not super
  important.
</div>
```

```html
<div class="alert alert-warning" role="alert">
  <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>
```

```html
<div class="alert alert-danger" role="alert">
  <strong>Oh snap!</strong> Change a few things up and try submitting again.
</div>
```

# Buttons in bootstrap

```html
<button type="button" class="btn btn-primary">Primary</button>
```

```html
<button type="button" class="btn btn-secondary">Secondary</button>
```

```html
<button type="button" class="btn btn-success">Success</button>
```

```html
<button type="button" class="btn btn-info">Info</button>
```

```html
<button type="button" class="btn btn-warning">Warning</button>
```

```html
<button type="button" class="btn btn-danger">Danger</button>
```

```html
<button type="button" class="btn btn-dark">Dark</button>
```

```html
<button type="button" class="btn btn-outline-primary">Primary</button>
```

```html
<button type="button" class="btn btn-outline-secondary">Secondary</button>
```

```html
<button type="button" class="btn btn-outline-success">Success</button>
```

```html
<button type="button" class="btn btn-outline-info">Info</button>
```

```html
<button type="button" class="btn btn-outline-info">Info</button>
```

```html
<button type="button" class="btn btn-outline-warning">Warning</button>
```

```html
<button type="button" class="btn btn-outline-danger">Danger</button>
```

```html
<button type="button" class="btn btn-outline-dark">Dark</button>
```

# Grids in bootstrap

```html
<div class="container">
  <!-- Content here -->
</div>
```

```html
<div class="container-fluid">
  <!-- A fluid container that uses the full witdh -->
</div>
```

```html
<!-- Equal width cols, same on all screen sizes -->
<div class="container">
  <div class="row">
    <!-- Page width is divided to 12 col -->
    <div class="col-4">25% width</div>
    <div class="col-4">25% width</div>
    <div class="col-4">25% width</div>
  </div>
</div>
```

# Images in bootstrap

```html
<img
  src="/images/pathToYourImage.png"
  class="img-fluid"
  alt="Responsive image"
/>
```

```html
<!-- Thumbnail -->
<img
  class="img-thumbnail"
  src="/images/pathToYourImage.png"
  alt="Thumbnail image"
/>
```

# Jumbotrons in bootstrap

```html
<div class="jumbotron">
  <h1 class="display-3">Hello, world!</h1>
  <p class="lead">
    This is a simple hero unit, a simple jumbotron-style component for calling
    extra attention to featured content or information.
  </p>
  <hr class="my-2" />
  <p>
    It uses utility classes for typography and spacing to space content out
    within the larger container.
  </p>
  <p class="lead">
    <a class="btn btn-primary btn-lg" href="#!" role="button">Some action</a>
  </p>
</div>
```

```html
<div class="jumbotron jumbotron-fluid">
  <div class="container">
    <h1 class="display-3">Fluid jumbotron</h1>
    <p class="lead">
      This is a modified jumbotron that occupies the entire horizontal space of
      its parent.
    </p>
  </div>
</div>
```

# Lists in bootstrap

```html
<ul class="list-group">
  <!-- Traditional list item -->
  <li class="list-group-item">Morbi leo risus</li>

  <!-- Active list item -->
  <li class="list-group-item active">Porta ac consectetur ac</li>

  <!-- Disabled list item -->
  <li class="list-group-item disabled">Vestibulum at eros</li>

  <!-- Primary coloured list item -->
  <li class="list-group-item list-group-item-primary">Vestibulum at eros</li>

  <!-- Secondary coloured list item -->
  <li class="list-group-item list-group-item-secondary">Vestibulum at eros</li>

  <!-- Success coloured list item -->
  <li class="list-group-item list-group-item-success">Vestibulum at eros</li>

  <!-- Info coloured list item -->
  <li class="list-group-item list-group-item-info">Vestibulum at eros</li>

  <!-- Warning coloured list item -->
  <li class="list-group-item list-group-item-warning">Vestibulum at eros</li>

  <!-- Danger coloured list item -->
  <li class="list-group-item list-group-item-danger">Vestibulum at eros</li>

  <!-- Dark coloured list item -->
  <li class="list-group-item list-group-item-dark">Vestibulum at eros</li>

  <!-- Light coloured list item -->
  <li class="list-group-item list-group-item-light">Vestibulum at eros</li>

  <!-- List item with badges -->
  <li class="list-group-item d-flex justify-content-between align-items-center">
    Cras justo odio
    <span class="badge badge-primary badge-pill">14</span>
  </li>
</ul>

<!-- Horizontal list group -->
<ul class="list-group list-group-horizontal">
  <li class="list-group-item">Cras justo odio</li>
  <li class="list-group-item">Dapibus ac facilisis in</li>
  <li class="list-group-item">Morbi leo risus</li>
</ul>
```

# Cards in bootstrap

```html
<div class="card">
  <img
    class="card-img-top"
    src="/images/pathToYourImage.png"
    alt="Card image cap"
  />
  <div class="card-body">
    <h4 class="card-title">Card title</h4>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of
      the card's content.
    </p>
    <a href="#!" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
```

# Accordions in bootstrap

```html
<div id="accordion" role="tablist">
  <div class="card">
    <div class="card-header" role="tab" id="headingOne">
      <h5 class="mb-0">
        <a
          data-toggle="collapse"
          href="#collapseOne"
          aria-expanded="true"
          aria-controls="collapseOne"
        >
          Collapsible Group Item #1
        </a>
      </h5>
    </div>

    <div
      id="collapseOne"
      class="collapse show"
      role="tabpanel"
      aria-labelledby="headingOne"
    >
      <div class="card-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus
        terry richardson ad squid.
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" role="tab" id="headingTwo">
      <h5 class="mb-0">
        <a
          class="collapsed"
          data-toggle="collapse"
          href="#collapseTwo"
          aria-expanded="false"
          aria-controls="collapseTwo"
        >
          Collapsible Group Item #2
        </a>
      </h5>
    </div>
    <div
      id="collapseTwo"
      class="collapse"
      role="tabpanel"
      aria-labelledby="headingTwo"
    >
      <div class="card-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus
        terry richardson ad squid.
      </div>
    </div>
  </div>
</div>
```

# Spinners in bootstrap

```html
<!-- Rotating circle -->
<div class="spinner-border" role="status">
  <span class="sr-only">Loading...</span>
</div>
```

```html
<!-- Growing circle -->
<div class="spinner-grow" role="status">
  <span class="sr-only">Loading...</span>
</div>
```

# Badges in bootstrap

```html
<span class="badge badge-primary">Primary</span>
```

```html
<span class="badge badge-secondary">Secondary</span>
```

```html
<span class="badge badge-success">Success</span>
```

```html
<span class="badge badge-info">Info</span>
```

```html
<span class="badge badge-warning">Warning</span>
```

```html
<span class="badge badge-danger">Danger</span>
```

```html
<span class="badge badge-light">Light</span>
```

```html
<span class="badge badge-dark">Dark</span>
```

```html
<span class="badge badge-pill badge-primary">Pill</span>
```

# Tables in bootstrap

```html
<table class="table">
  <thead>
    <tr>
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
    </tr>
  </tbody>
</table>
```

# Modals in bootstrap

# Navs in bootstrap

# Texts in bootstrap

# Colors in bootstrap

# Dropdowns in bootstrap

# Borders in bootstrap

# Spacing in bootstrap

# Sizing in bootstrap

# Positioning in bootstrap

# Button modifiers in bootstrap

# Button groups in bootstrap

# Forms in bootstrap

# Displays in bootstrap

# Pagination in bootstrap

# Form input group in bootstrap

# Toasts in bootstrap
