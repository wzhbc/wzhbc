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
### Hi there 👋
<!--
**wzhbc/wzhbc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
