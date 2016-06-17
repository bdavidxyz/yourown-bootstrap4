<div class="sub-header">
  <h2 class="component-title" id="navs">Navs</h2>
</div>

<div class="row">
  <div class="col-lg-4">
    <h3 class="component-title">Vertical nav</h3>

    <ul class="nav">
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Another link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
  <div class="col-lg-4">
  <h3 class="component-title">Inline</h3>


    <nav class="nav">
      <a class="nav-link active" href="#">Active</a>
      <a class="nav-link" href="#">Link</a>
      <a class="nav-link" href="#">Another link</a>
      <a class="nav-link disabled" href="#">Disabled</a>
    </nav>

  </div>
  <div class="col-lg-4">
    <h3 class="component-title">Using data attributes</h3>

    <div role="tabpanel">
      <!-- Nav tabs -->
      <ul class="nav nav-tabs" role="tablist">
        <li class="nav-item">
          <a class="nav-link active" data-toggle="tab" href="#home" role="tab">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" data-toggle="tab" href="#profile" role="tab">Profile</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" data-toggle="tab" href="#messages" role="tab">Messages</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" data-toggle="tab" href="#settings" role="tab">Settings</a>
        </li>
      </ul>

      <!-- Tab panes -->
      <div class="tab-content">
        <div class="tab-pane active" id="home" role="tabpanel">...</div>
        <div class="tab-pane" id="profile" role="tabpanel">...</div>
        <div class="tab-pane" id="messages" role="tabpanel">...</div>
        <div class="tab-pane" id="settings" role="tabpanel">...</div>
      </div>
    </div>
  </div>
</div>
<div class="row">
  <div class="col-lg-4">
    <h3 class="component-title">Tabs</h3>

    <ul class="nav nav-tabs">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Another link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
  <div class="col-lg-4">
    <h3 class="component-title">Pills</h3>

    <ul class="nav nav-pills">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Another link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
  <div class="col-lg-4">
    <h3 class="component-title">Stacked pills</h3>

    <ul class="nav nav-pills nav-stacked">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Another link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
</div>
<div class="row">
  <div class="col-lg-4">
    <h3 class="component-title">Tabs with dropdowns</h3>

    <ul class="nav nav-tabs">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false">Dropdown</a>
        <div class="dropdown-menu">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Separated link</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Another link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
  <div class="col-lg-4">
    <h3 class="component-title">Pills with dropdowns</h3>

    <ul class="nav nav-pills">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false">Dropdown</a>
        <div class="dropdown-menu">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Separated link</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Another link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
  <div class="col-lg-4">
    <h3 class="component-title">JavaScript behavior</h3>

    <div class="bd-example bd-example-tabs" role="tabpanel">
      <ul class="nav nav-tabs" id="myTab" role="tablist">
        <li class="nav-item">
          <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-expanded="true">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile">Profile</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false">
            Dropdown
          </a>
          <div class="dropdown-menu">
            <a class="dropdown-item" id="dropdown1-tab" href="#dropdown1" role="tab" data-toggle="tab" aria-controls="dropdown1">@fat</a>
            <a class="dropdown-item" id="dropdown2-tab" href="#dropdown2" role="tab" data-toggle="tab" aria-controls="dropdown2">@mdo</a>
          </div>
        </li>
      </ul>
      <div class="tab-content" id="myTabContent">
        <div role="tabpanel" class="tab-pane fade in active" id="home" aria-labelledBy="home-tab">
          <p>Raw denim you probably haven't heard of them jean shorts Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro keffiyeh dreamcatcher synth. Cosby sweater eu banh mi, qui irure terry richardson ex squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan american apparel, butcher voluptate nisi qui.</p>
        </div>
        <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledBy="profile-tab">
          <p>Food truck fixie locavore, accusamus mcsweeney's marfa nulla single-origin coffee squid. Exercitation +1 labore velit, blog sartorial PBR leggings next level wes anderson artisan four loko farm-to-table craft beer twee. Qui photo booth letterpress, commodo enim craft beer mlkshk aliquip jean shorts ullamco ad vinyl cillum PBR. Homo nostrud organic, assumenda labore aesthetic magna delectus mollit. Keytar helvetica VHS salvia yr, vero magna velit sapiente labore stumptown. Vegan fanny pack odio cillum wes anderson 8-bit, sustainable jean shorts beard ut DIY ethical culpa terry richardson biodiesel. Art party scenester stumptown, tumblr butcher vero sint qui sapiente accusamus tattooed echo park.</p>
        </div>
        <div class="tab-pane fade" id="dropdown1" role="tabpanel" aria-labelledBy="dropdown1-tab">
          <p>Etsy mixtape wayfarers, ethical wes anderson tofu before they sold out mcsweeney's organic lomo retro fanny pack lo-fi farm-to-table readymade. Messenger bag gentrify pitchfork tattooed craft beer, iphone skateboard locavore carles etsy salvia banksy hoodie helvetica. DIY synth PBR banksy irony. Leggings gentrify squid 8-bit cred pitchfork. Williamsburg banh mi whatever gluten-free, carles pitchfork biodiesel fixie etsy retro mlkshk vice blog. Scenester cred you probably haven't heard of them, vinyl craft beer blog stumptown. Pitchfork sustainable tofu synth chambray yr.</p>
        </div>
        <div class="tab-pane fade" id="dropdown2" role="tabpanel" aria-labelledBy="dropdown2-tab">
          <p>Trust fund seitan letterpress, keytar raw denim keffiyeh etsy art party before they sold out master cleanse gluten-free squid scenester freegan cosby sweater. Fanny pack portland seitan DIY, art party locavore wolf cliche high life echo park Austin. Cred vinyl keffiyeh DIY salvia PBR, banh mi before they sold out farm-to-table VHS viral locavore cosby sweater. Lomo wolf viral, mustache readymade thundercats keffiyeh craft beer marfa ethical. Wolf salvia freegan, sartorial keffiyeh echo park vegan.</p>
        </div>
      </div>
    </div>

  </div>
</div>
































