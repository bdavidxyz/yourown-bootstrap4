
<div class="sub-header">
  <h2 class="component-title" id="forms">Forms</h2>
</div>

<div class="row">
  <div class="col-lg-6">


    <h3 class="component-title">Form controls</h3>



    <form>
      <fieldset class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Enter email">
        <small class="text-muted">We'll never share your email with anyone else.</small>
      </fieldset>
      <fieldset class="form-group">
        <label for="exampleInputPassword1">Password</label>
        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
      </fieldset>
      <fieldset class="form-group">
        <label for="exampleSelect1">Example select</label>
        <select class="form-control" id="exampleSelect1">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </fieldset>
      <fieldset class="form-group">
        <label for="exampleSelect2">Example multiple select</label>
        <select multiple class="form-control" id="exampleSelect2">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </fieldset>
      <fieldset class="form-group">
        <label for="exampleTextarea">Example textarea</label>
        <textarea class="form-control" id="exampleTextarea" rows="3"></textarea>
      </fieldset>
      <fieldset class="form-group">
        <label for="exampleInputFile">File input</label>
        <input type="file" class="form-control-file" id="exampleInputFile">
        <small class="text-muted">This is some placeholder block-level help text for the above input. It's a bit lighter and easily wraps to a new line.</small>
      </fieldset>
      <div class="radio">
        <label>
          <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1" checked>
          Option one is this and that&mdash;be sure to include why it's great
        </label>
      </div>
      <div class="radio">
        <label>
          <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">
          Option two can be something else and selecting it will deselect option one
        </label>
      </div>
      <div class="radio disabled">
        <label>
          <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3" disabled>
          Option three is disabled
        </label>
      </div>
      <div class="checkbox">
        <label>
          <input type="checkbox"> Check me out
        </label>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
  <div class="col-lg-6">

    <h3 class="component-title">Form groups</h3>

    <form>
      <fieldset class="form-group">
        <label for="formGroupExampleInput">Example label</label>
        <input type="text" class="form-control" id="formGroupExampleInput" placeholder="Example input">
      </fieldset>
      <fieldset class="form-group">
        <label for="formGroupExampleInput2">Another label</label>
        <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="Another input">
      </fieldset>
    </form>

    <h3 class="component-title">Inline forms</h3>




    <h4 class="component-title">Visible labels</h4>

    <form class="form-inline">
      <div class="form-group">
        <label for="exampleInputName2">Name</label>
        <input type="text" class="form-control" id="exampleInputName2" placeholder="Jane Doe">
      </div>
      <div class="form-group">
        <label for="exampleInputEmail2">Email</label>
        <input type="email" class="form-control" id="exampleInputEmail2" placeholder="jane.doe@example.com">
      </div>
      <button type="submit" class="btn btn-primary">Send invitation</button>
    </form>


    <h4 class="component-title">Hidden labels</h4>


    <form class="form-inline">
      <div class="form-group">
        <label class="sr-only" for="exampleInputEmail3">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail3" placeholder="Enter email">
      </div>
      <div class="form-group">
        <label class="sr-only" for="exampleInputPassword3">Password</label>
        <input type="password" class="form-control" id="exampleInputPassword3" placeholder="Password">
      </div>
      <div class="checkbox">
        <label>
          <input type="checkbox"> Remember me
        </label>
      </div>
      <button type="submit" class="btn btn-primary">Sign in</button>
    </form>

    <form class="form-inline">
      <div class="form-group">
        <label class="sr-only" for="exampleInputAmount">Amount (in dollars)</label>
        <div class="input-group">
          <div class="input-group-addon">$</div>
          <input type="text" class="form-control" id="exampleInputAmount" placeholder="Amount">
          <div class="input-group-addon">.00</div>
        </div>
      </div>
      <button type="submit" class="btn btn-primary">Transfer cash</button>
    </form>
  </div>
</div>



<h3 class="component-title">Using the Grid</h3>


<form>
  <div class="form-group row">
    <label for="inputEmail3" class="col-sm-2 form-control-label">Email</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
    </div>
  </div>
  <div class="form-group row">
    <label for="inputPassword3" class="col-sm-2 form-control-label">Password</label>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword3" placeholder="Password">
    </div>
  </div>
  <div class="form-group row">
    <label class="col-sm-2">Radios</label>
    <div class="col-sm-10">
      <div class="radio">
        <label>
          <input type="radio" name="gridRadios" id="gridRadios1" value="option1" checked>
          Option one is this and that&mdash;be sure to include why it's great
        </label>
      </div>
      <div class="radio">
        <label>
          <input type="radio" name="gridRadios" id="gridRadios2" value="option2">
          Option two can be something else and selecting it will deselect option one
        </label>
      </div>
      <div class="radio disabled">
        <label>
          <input type="radio" name="gridRadios" id="gridRadios3" value="option3" disabled>
          Option three is disabled
        </label>
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label class="col-sm-2">Checkbox</label>
    <div class="col-sm-10">
      <div class="checkbox">
        <label>
          <input type="checkbox"> Check me out
        </label>
      </div>
    </div>
  </div>
  <div class="form-group row">
    <div class="col-sm-offset-2 col-sm-10">
      <button type="submit" class="btn btn-secondary">Sign in</button>
    </div>
  </div>
</form>

<h3 class="component-title">Checkboxes and radios</h3>


<h4 class="component-title">Default (stacked)</h4>

<div class="checkbox">
  <label>
    <input type="checkbox" value="">
    Option one is this and that&mdash;be sure to include why it's great
  </label>
</div>
<div class="checkbox disabled">
  <label>
    <input type="checkbox" value="" disabled>
    Option two is disabled
  </label>
</div>

<div class="radio">
  <label>
    <input type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
    Option one is this and that&mdash;be sure to include why it's great
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
    Option two can be something else and selecting it will deselect option one
  </label>
</div>
<div class="radio disabled">
  <label>
    <input type="radio" name="exampleRadios" id="exampleRadios3" value="option3" disabled>
    Option three is disabled
  </label>
</div>

<h4 class="component-title">Inline</h4>

<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox1" value="option1"> 1
</label>
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox2" value="option2"> 2
</label>
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox3" value="option3"> 3
</label>

<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1"> 1
</label>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2"> 2
</label>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3"> 3
</label>


<h4 class="component-title">Without labels</h4>

<div class="checkbox">
  <label>
    <input type="checkbox" id="blankCheckbox" value="option1">
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="blankRadio" id="blankRadio1" value="option1">
  </label>
</div>

<h3 class="component-title">Static controls</h3>

<form>
  <div class="form-group row">
    <label class="col-sm-2 form-control-label">Email</label>
    <div class="col-sm-10">
      <p class="form-control-static">email@example.com</p>
    </div>
  </div>
  <div class="form-group row">
    <label for="inputPassword" class="col-sm-2 form-control-label">Password</label>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword" placeholder="Password">
    </div>
  </div>
</form>

<form class="form-inline">
  <div class="form-group">
    <label class="sr-only">Email</label>
    <p class="form-control-static">email@example.com</p>
  </div>
  <div class="form-group">
    <label for="inputPassword2" class="sr-only">Password</label>
    <input type="password" class="form-control" id="inputPassword2" placeholder="Password">
  </div>
  <button type="submit" class="btn btn-primary">Confirm identity</button>
</form>

<h3 class="component-title">Disabled states</h3>

<form>
  <fieldset disabled>
    <div class="form-group">
      <label for="disabledTextInput">Disabled input</label>
      <input type="text" id="disabledTextInput" class="form-control" placeholder="Disabled input">
    </div>
    <div class="form-group">
      <label for="disabledSelect">Disabled select menu</label>
      <select id="disabledSelect" class="form-control">
        <option>Disabled select</option>
      </select>
    </div>
    <div class="checkbox">
      <label>
        <input type="checkbox"> Can't check this
      </label>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </fieldset>
</form>


<h3 class="component-title">Readonly inputs</h3>


<input class="form-control" type="text" placeholder="Readonly input here…" readonly>

<h3 class="component-title">Control sizing</h3>


<input class="form-control form-control-lg" type="text" placeholder=".form-control-lg">
<input class="form-control" type="text" placeholder="Default input">
<input class="form-control form-control-sm" type="text" placeholder=".form-control-sm">

<select class="form-control form-control-lg"></select>
<select class="form-control"></select>
<select class="form-control form-control-sm"></select>

<h3 class="component-title">Column sizing</h3>

Wrap inputs in grid columns, or any custom parent element, to easily enforce desired widths.

<div class="row">
  <div class="col-xs-2">
    <input type="text" class="form-control" placeholder=".col-xs-2">
  </div>
  <div class="col-xs-3">
    <input type="text" class="form-control" placeholder=".col-xs-3">
  </div>
  <div class="col-xs-4">
    <input type="text" class="form-control" placeholder=".col-xs-4">
  </div>
</div>


<h3 class="component-title">Help text</h3>

<small class="text-muted">
  Some inline text with a small tag looks like this.
</small>


<p class="text-muted">
  A block of help text that breaks onto a new line and may extend beyond one line.
</p>


<h3 class="component-title">Validation</h3>

<div class="form-group has-success">
  <label class="form-control-label" for="inputSuccess1">Input with success</label>
  <input type="text" class="form-control form-control-success" id="inputSuccess1">
</div>
<div class="form-group has-warning">
  <label class="form-control-label" for="inputWarning1">Input with warning</label>
  <input type="text" class="form-control form-control-warning" id="inputWarning1">
</div>
<div class="form-group has-danger">
  <label class="form-control-label" for="inputDanger1">Input with danger</label>
  <input type="text" class="form-control form-control-danger" id="inputDanger1">
</div>

<div class="checkbox has-success">
  <label>
    <input type="checkbox" id="checkboxSuccess" value="option1">
    Checkbox with success
  </label>
</div>
<div class="checkbox has-warning">
  <label>
    <input type="checkbox" id="checkboxWarning" value="option1">
    Checkbox with warning
  </label>
</div>
<div class="checkbox has-danger">
  <label>
    <input type="checkbox" id="checkboxDanger" value="option1">
    Checkbox with danger
  </label>
</div>



<h3 class="component-title">Custom forms</h3>

<h4 class="component-title">Checkboxes</h4>

<label class="c-input c-checkbox">
  <input type="checkbox">
  <span class="c-indicator"></span>
  Check this custom checkbox
</label>

<div class="bd-example bd-example-indeterminate">
  <label class="c-input c-checkbox">
    <input type="checkbox">
    <span class="c-indicator"></span>
    Check this custom checkbox
  </label>
</div>

<h4 class="component-title">Radios</h4>

<label class="c-input c-radio">
  <input id="radio1" name="radio" type="radio">
  <span class="c-indicator"></span>
  Toggle this custom radio
</label>
<label class="c-input c-radio">
  <input id="radio2" name="radio" type="radio">
  <span class="c-indicator"></span>
  Or toggle this other custom radio
</label>


<h4 class="component-title">Stacked</h4>

<div class="c-inputs-stacked">
  <label class="c-input c-radio">
    <input id="radioStacked1" name="radio-stacked" type="radio">
    <span class="c-indicator"></span>
    Toggle this custom radio
  </label>
  <label class="c-input c-radio">
    <input id="radioStacked2" name="radio-stacked" type="radio">
    <span class="c-indicator"></span>
    Or toggle this other custom radio
  </label>
</div>

<h4 class="component-title">Select menu</h4>

<select class="c-select">
  <option selected>Open this select menu</option>
  <option value="1">One</option>
  <option value="2">Two</option>
  <option value="3">Three</option>
</select>

<h3 class="component-title">File browser</h3>

<label class="file">
  <input type="file" id="file">
  <span class="file-custom"></span>
</label>


