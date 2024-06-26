```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>DOM Manipulation</title>
    <style>
      h3 {
        margin-bottom: 0px;
      }

      #style {
        width: 200px;
        height: 100px;
        border: 1px rgb(126, 126, 126) solid;
        background-color: aliceblue;
        padding: 10px;
      }
    </style>
  </head>

  <body>
    <h1>DOM MANIPULATION</h1>

    <div>
      <h3>Accessing Element using ID and Class</h3>
      <div>
        <div id="first-div" class="sample-div">Sample Div</div>
        <div id="second-div" class="sample-div">Div</div>
        <div id="third-div" class="sample-div">Div 3</div>
      </div>
    </div>

    <div>
      <h3>Accessing Element using TagName</h3>
      <h3>Unordered List</h3>
      <ul>
        <li class="unordered-list">Unordered List Item 1</li>
        <li class="unordered-list">Unordered List Item 2</li>
        <li class="unordered-list">Unordered List Item 3</li>
      </ul>
    </div>

    <div>
      <h3>Accessing Element using Query Selector</h3>
      <h3>Ordered List</h3>
      <ol>
        <li class="ordered-list">Ordered List Item 1</li>
        <li class="ordered-list">Ordered List Item 2</li>
        <li class="ordered-list">Ordered List Item 3</li>
      </ol>
    </div>

    <div>
      <h3>Adding Event Listener</h3>
      <div>
        <div id="button-div">Click the button below!</div>
        <button id="button">Click me!</button>
      </div>
    </div>

    <div>
      <h3>Appending New Elements</h3>
      <div>
        <div id="append">Existing content</div>
      </div>
    </div>

    <div>
      <h3>Removing Elements</h3>
      <div id="remove">
        <div>Element to be removed</div>
      </div>
    </div>

    <div>
      <h3>Updating Element Attributes</h3>
      <div>
        <img
          id="image"
          style="height: 50px"
          src="https://cdn-icons-png.flaticon.com/512/624/624106.png"
          alt="Original Image"
        />
      </div>
    </div>

    <div>
      <h3>Manipulating Element Styles</h3>
      <div id="style">
        <div id="mode">Light Mode</div>
        <div>Welcome to my profile</div>
      </div>
    </div>

    <script src="./app.js"></script>
  </body>
</html>
```
