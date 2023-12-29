```{=html}
<ul id="choose-your-tool" class="nav nav-tabs" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="docs/deep-learning/">
      <img src="docs/get-started/images/vscode-logo.png">Deep Learning
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="jupyter.html">
      <img src="docs/get-started/images/jupyter-logo.png">Human Computer Interaction
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="rstudio.html">
      <img src="docs/get-started/images/rstudio-logo.png">College Research
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="neovim.html">
      <img src="docs/get-started/images/neovim-logo.svg">Machine Learning
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="text-editor.html">
      <img src="docs/get-started/images/text-editor-logo.png" id="text-editor-logo">Editor
    </a>
  </li>
</ul>

<script type="text/javascript">
document.addEventListener("DOMContentLoaded", function() {
  // get file name
  const filename = window.location.pathname.split("/").slice(-1)[0];
  
  // latch active
  const toolLinks = window.document.querySelectorAll("#choose-your-tool a");
  for (const tool of toolLinks) {
    if (tool.href.endsWith(filename)) {
      tool.classList.add("active");
      break;
    }
  }
  
   // save in local storage
  window.localStorage.setItem("tutorialTool", filename);
});

</script>
```
