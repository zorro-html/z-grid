# grid

12 columns per row

Inspired from:
http://www.sitepoint.com/understanding-css-grid-systems/

## Classes

- `row`
- `column column-*`

## Examples

```
<style>
  #z-grid-outer {
    padding: 20px;
  }

  #z-grid-outer .column {
    background: #eee;
    border: 1px solid #ccc;
    border-radius: 4px;
    color: #777;
    padding: 5px;
    min-height: 30px;
    text-align: center;
  }

  #z-grid-outer .row {
    margin-bottom: 10px;
  }

  #z-grid-outer .row:last-child {
    margin-bottom: 0;
  }

  #z-grid-outer .column .column {
    color: #eee;
    background: #333;
    border-color: #000;
  }
</style>

<div id="z-grid-outer" style="width: 480px;">
  <div class="row">
    <div class="column column-4"></div>
    <div class="column column-4"></div>
    <div class="column column-4"></div>
  </div>
  <div class="row">
    <div class="column column-2"></div>
    <div class="column column-4"></div>
    <div class="column column-4"></div>
    <div class="column column-2"></div>
  </div>
  <div class="row">
    <div class="column column-5"></div>
    <div class="column column-7"></div>
  </div>
  <div class="row">
    <div class="column column-6">
      <div class="row">
        <div class="column column-6"></div>
        <div class="column column-6"></div>
      </div>
      <div class="row">
        <div class="column column-3"></div>
        <div class="column column-3"></div>
        <div class="column column-3"></div>
        <div class="column column-3"></div>
      </div>
      <div class="row">
        <div class="column column-4"></div>
        <div class="column column-4"></div>
        <div class="column column-4"></div>
      </div>
    </div>
    <div class="column column-6">
      <div class="row">
        <div class="column column-7"></div>
        <div class="column column-3"></div>
        <div class="column column-2"></div>
      </div>
      <div class="row">
        <div class="column column-2"></div>
        <div class="column column-2"></div>
        <div class="column column-4"></div>
        <div class="column column-2"></div>
        <div class="column column-2"></div>
      </div>
      <div class="row">
        <div class="column column-9"></div>
        <div class="column column-3"></div>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="column column-8"></div>
    <div class="column column-4"></div>
  </div>
  <div class="row">
    <div class="column column-1"></div>
    <div class="column column-3"></div>
    <div class="column column-4"></div>
    <div class="column column-3"></div>
    <div class="column column-1"></div>
  </div>
  <div class="row">
    <div class="column column-3"></div>
    <div class="column column-3"></div>
    <div class="column column-3"></div>
    <div class="column column-3"></div>
  </div>
  <div class="row">
    <div class="column column-12"></div>
  </div>
</div>
```
