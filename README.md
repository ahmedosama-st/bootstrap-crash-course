# Bootstrap Cheatsheet 1.0.0

## Made by **[SecTheater](https://github.com/SecTheater/)**

### Don't forget to follow us ^^

> [Facebook page](https://bit.ly/39dTot4)

> [Facebook group](https://bit.ly/39c5YsH)

> [Telegram channel](https://bit.ly/35Zd41Z)

> [Telegram group](https://bit.ly/361mzOd)

> [Discord](https://bit.ly/39c8Ohw)

> [Youtube](https://bit.ly/2J3v95R)

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
<table class="table table-bordered table-hover table-responsive">
  <thead class="thead-dark">
    <tr class="table-warning">
      <th>#</th>
      <th>First Name</th>
      <th>Last Name</th>
    </tr>
  </thead>
  <tbody>
    <tr class="table-success">
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
    </tr>
  </tbody>
</table>
```

# Modals in bootstrap

```html
<!-- Button trigger modal -->
<button
  type="button"
  class="btn btn-primary"
  data-toggle="modal"
  data-target="#exampleModal"
>
  Launch demo modal
</button>

<!-- Modal -->
<div
  class="modal"
  id="exampleModal"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button
          type="button"
          class="close"
          data-dismiss="modal"
          aria-label="Close"
        >
          <span aria-hidden="true">×</span>
        </button>
      </div>
      <div class="modal-body">...</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">
          Close
        </button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```

# Navs in bootstrap

```html
<!-- Lists also can have nav classes and drop downs -->
<ul class="nav nav-tabs">
  <li class="nav-item">
    <a class="nav-link active" href="#!">Active</a>
  </li>
  <li class="nav-item dropdown">
    <a
      class="nav-link dropdown-toggle"
      data-toggle="dropdown"
      href="#"
      role="button"
      aria-haspopup="true"
      aria-expanded="false"
    >
      Dropdown</a
    >
    <div class="dropdown-menu">
      <a class="dropdown-item" href="#!">Action</a>
      <a class="dropdown-item" href="#!">Another action</a>
    </div>
  </li>
</ul>
```

# Texts in bootstrap

```html
<!-- Text modifications -->
<p class="font-weight-bold">Bold text.</p>
<p class="font-weight-light">Light text.</p>
<p class="font-weight-normal">Normal weight text.</p>
<p class="text-decoration-none">This text is not decorated</p>
<p class="font-italic">Italicized text.</p>
<p class="text-monospace">This is in monospace</p>
<p class="text-justify">Justified text.</p>
<p class="text-nowrap">No wrap text.</p>

<!-- Aligns -->
<p class="text-left">Left aligned text on all viewport sizes.</p>
<p class="text-right">Right aligned text on all viewport sizes.</p>
<p class="text-center">Center aligned text on all viewport sizes.</p>
<p class="text-lowercase">lowercased text.</p>
<p class="text-uppercase">uppercased text.</p>
<p class="text-capitalize">capitalized text.</p>
<p class="text-muted">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-primary">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-success">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-danger">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-info">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-warning">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-dark">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-light">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
<p class="text-secondary">
  Heron alap ceroau kesse elex ruta. Tauru hemed ela meliado egeb selof.
</p>
```

# Colors in bootstrap

```html
<div class="bg-primary text-white">
  Nullam id dolor id nibh ultricies vehicula ut id elit.
</div>
<div class="bg-secondary text-white">
  Nullam id dolor id nibh ultricies vehicula ut id elit.
</div>
<div class="bg-success text-white">
  Duis mollis, est non commodo luctus, nisi erat porttitor ligula.
</div>
<div class="bg-info text-white">
  Maecenas sed diam eget risus varius blandit sit amet non magna.
</div>
<div class="bg-warning text-white">
  Etiam porta sem malesuada magna mollis euismod.
</div>
<div class="bg-danger text-white">
  Donec ullamcorper nulla non metus auctor fringilla.
</div>
<div class="bg-light">Cras mattis consectetur purus sit amet fermentum.</div>
<div class="bg-dark text-white">
  Nullam id dolor id nibh ultricies vehicula ut id elit.
</div>
<div class="bg-white">
  Nullam id dolor id nibh ultricies vehicula ut id elit.
</div>
```

# Dropdowns in bootstrap

```html
<div class="dropdown">
  <button
    class="btn btn-secondary dropdown-toggle"
    type="button"
    id="dropdownMenu1"
    data-toggle="dropdown"
    aria-haspopup="true"
    aria-expanded="false"
  >
    Dropdown
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenu1">
    <a class="dropdown-item" href="#!">Action</a>
    <a class="dropdown-item" href="#!">Another action</a>
  </div>
</div>
```

# Borders in bootstrap

```html
<!-- You can apply colors here too just change primary to the color you want
Also you can change the weight of the border and the padding -->
<span class="p-1 border border-primary border-0">Hello World</span>
<span class="p-2 border border-primary border-top-1">Hello World</span>
<span class="p-3 border border-primary border-right-2">Hello World</span>
<span class="p-4 border border-primary border-bottom-3">Hello World</span>
<span class="p-5 border border-primary border-left-4">Hello World</span>
```

# Spacing in bootstrap

```html
<!--
  Spacing elements in bootstrap is pretty easy
  You just use class="m-n" for margins and replace n with numbers
  And easily get margins all around the element
  Also you can use class="p-n" for paddings and again, replace n with numbers
  Thus you get paddings all around the element
  Or use class="ml-n" to add left margin only
  Or class="mr-n" to add right margin only
  Or class="ml-n" to add left margin only
  Or class="mt-n" to add top margin only
  Or class="mb-n" to add bottom margin only
  Or class="mx-n" to add horizontal margins only (left and right)
  Or class="my-n" to add vertical margins only (top and bottom )
  Or class="px-n" to add horizontal paddings only (left and right)
  Or class="py-n" to add vertical paddings only (top and bottom)
-->

<!-- Margin classes  -->
<div class="m-0 bg-primary">Spaced Div</div>
<div class="mt-0 bg-primary">Spaced Div</div>
<div class="mb-0 bg-primary">Spaced Div</div>
<div class="ml-0 bg-primary">Spaced Div</div>
<div class="mr-0 bg-primary">Spaced Div</div>
<div class="mx-0 bg-primary">Spaced Div</div>
<div class="my-0 bg-primary">Spaced Div</div>

<!-- Padding classes  -->
<div class="p-0 bg-primary">Spaced Div</div>
<div class="pt-0 bg-primary">Spaced Div</div>
<div class="pb-0 bg-primary">Spaced Div</div>
<div class="pl-0 bg-primary">Spaced Div</div>
<div class="pr-0 bg-primary">Spaced Div</div>
<div class="px-0 bg-primary">Spaced Div</div>
<div class="py-0 bg-primary">Spaced Div</div>
```

# Sizing in bootstrap

```html
<!--
  Sizing elements in bootstrap is pretty straight forward
  class="w-n" is how you size an element to have given width,
  Similarily, class="h-n" defines the height, mh-n is maximum-height can have,
  and mw-n is maximum-weight can have.
-->

<div class="w-25 p-3" style="background-color: #eee;">Width 25%</div>
<div class="w-50 p-3" style="background-color: #eee;">Width 50%</div>
<div class="w-75 p-3" style="background-color: #eee;">Width 75%</div>
<div class="w-100 p-3" style="background-color: #eee;">Width 100%</div>

<!-- 10 stands for 100%, similarily, 1 for 10% etc.. -->
<img class="mw-10" src="#" alt="Max-width 100%" />
<img class="mh-10" src="#" alt="Max-height 100%" />
```

# Positioning in bootstrap

```html
<!--
  Aligning elements is also pretty obvious in bootstrap
  You just specify where you would like to align this element
  Also you can define fixed, sticky and floating elements.
-->
<span class="align-baseline">baseline</span>
<span class="align-top">top</span>
<span class="align-middle">middle</span>
<span class="align-bottom">bottom</span>
<span class="align-text-top">text-top</span>
<span class="align-text-bottom">text-bottom</span>

<div class="fixed-top bg-primary" style="">Fixed top</div>
<div class="fixed-bottom bg-primary" style="">Fixed bottom</div>
<div class="sticky-top bg-primary" style="">Sticky top</div>
<div class="float-left">Float left on all viewport sizes</div>
<div class="float-right">Float right on all viewport sizes</div>
```

# Button modifiers in bootstrap

```html
<!--
  Button modifiers are literally modifying buttons to have
  more attributes, like modifiying size to larger or smaller,
  active or disabled status etc..
-->
<button type="button" class="btn btn-primary btn-lg">Large button</button>
<button type="button" class="btn btn-primary btn-sm">Small button</button>
<button type="button" class="btn btn-primary btn-lg btn-block">
  Block level button
</button>
<a
  href="#!"
  class="btn btn-primary btn-lg active"
  role="button"
  aria-pressed="true"
  >Primary link</a
>
<button type="button" class="btn btn-lg btn-primary" disabled="">
  Disabled button
</button>
```

# Button groups in bootstrap

```html
<!--
  Button groups are classes to support addons to buttons
  like adding font-awesome icons next to buttons or grouping
  multiple buttons together
  and you can apply button modifiers to it too.
-->
<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-secondary">Left</button>
  <button type="button" class="btn btn-secondary">Middle</button>
  <button type="button" class="btn btn-secondary">Right</button>
</div>
```

# Forms in bootstrap

```html
<!--
  Forms in bootstrap can be inlined or grouped
  also modifiers can be applied to inputs.
-->

<!-- Grouped form -->
<form>
  <div class="form-group">
    <label for="formGroupExampleInput">Example label</label>
    <input
      type="text"
      class="form-control"
      id="formGroupExampleInput"
      placeholder="Example input"
    />
  </div>
  <div class="form-group">
    <label for="formGroupExampleInput2">Another label</label>
    <input
      type="text"
      class="form-control"
      id="formGroupExampleInput2"
      placeholder="Another input"
    />
  </div>
</form>

<!-- Inline form with font-awesome addon to input -->
<form class="form-inline">
  <label class="sr-only" for="inlineFormInputName2">Name</label>
  <input
    type="text"
    class="form-control mb-2 mr-sm-2"
    id="inlineFormInputName2"
    placeholder="Jane Doe"
  />

  <label class="sr-only" for="inlineFormInputGroupUsername2">Username</label>
  <div class="input-group mb-2 mr-sm-2">
    <div class="input-group-prepend">
      <div class="input-group-text">
        <i class="fa fa-envelope" aria-hidden="true"></i>
      </div>
    </div>
    <input
      type="text"
      class="form-control"
      id="inlineFormInputGroupUsername2"
      placeholder="Username"
    />
  </div>

  <button type="submit" class="btn btn-primary mb-2">Submit</button>
</form>
```

# Displays in bootstrap

```html
<!--
  Displaying elements in bootstrap is easy as typing d-block, d-flex etc..
-->
<span class="d-block bg-primary">d-block</span>
<div class="d-flex bg-primary">d-flex</div>
<div class="d-inline bg-primary">d-inline</div>
<div class="d-inline-block bg-primary">d-inline-block</div>
<div class="d-inline-flex bg-primary">d-inline-flex</div>
<div class="d-none">d-none"&gt;This</div>
```

# Pagination in bootstrap

```html
<!-- Pagination elements can have also active, disabled, sm and lg modifiers -->
<nav aria-label="...">
  <ul class="pagination pagination-lg">
    <li class="page-item disabled">
      <a class="page-link" href="#!" tabindex="-1">Previous</a>
    </li>
    <li class="page-item"><a class="page-link" href="#!">1</a></li>
    <li class="page-item active">
      <a class="page-link" href="#!"
        >2 <span class="sr-only">(current)</span></a
      >
    </li>
    <li class="page-item"><a class="page-link" href="#!">3</a></li>
    <li class="page-item">
      <a class="page-link" href="#!">Next</a>
    </li>
  </ul>
</nav>
```

# Form input group in bootstrap

```html
<!--
  Form-input groups is simply adding addons to input as we saw previously
  you can add left addon, right addon, dropdowns and even other inputs addons to your input
-->

<div class="input-group">
  <div class="input-group-prepend">
    <button
      class="btn btn-primary dropdown-toggle"
      type="button"
      data-toggle="dropdown"
      aria-haspopup="true"
      aria-expanded="false"
    >
      Dropdown
    </button>
    <div class="dropdown-menu">
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
    </div>
  </div>
  <input
    type="text"
    class="form-control"
    aria-label="Text input with dropdown button"
  />
</div>
```

# Toasts in bootstrap

```html
<!--
  Toasts is simply a flash message like a notification
  and it's dismissble
-->
<!-- Note a custom script is used to activate toasts:
$('.toast').toast();
-->

<div
  class="toast fade show"
  role="alert"
  aria-live="assertive"
  aria-atomic="true"
>
  <div class="toast-header">
    <strong class="mr-auto">Bootstrap</strong>
    <small>11 mins ago</small>
    <button
      type="button"
      class="ml-2 mb-1 close"
      data-dismiss="toast"
      aria-label="Close"
    >
      <span aria-hidden="true">×</span>
    </button>
  </div>
  <div class="toast-body">Hello, world! This is a toast message.</div>
</div>
```

---
