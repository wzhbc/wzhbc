<html>
  <head>
    <style>
      body {
        background: #ffb69e;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
      }
      .content {
        color: red;
        font-size: 30px;
      }
    </style>
    <script type='text/javascript'>
      const nodeHtmlToImage = require('node-html-to-image')
      nodeHtmlToImage({
        output: './image.png',
        html: '<html><body>Hello world!</body></html>'
      }).then(() => console.log('The image was created successfully!'))
    </script>
  </head>
  <body>
    <div id="wrapper">
      <div class="content">I am a colorful content</div>
    </div>
  </body>
</html>
### Hi there š
<!--
**wzhbc/wzhbc** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
