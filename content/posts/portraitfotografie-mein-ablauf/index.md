+++
title = "Portraitfotografie > mein Ablauf "
date = "2023-10-25"
draft = false
pinned = false
image = "screenshot-2023-10-25-at-21.39.12.jpeg"
+++
/** @type { import('@storybook/react-webpack5').StorybookConfig } */
const config = {
  stories: ["../src/**/*.mdx", "../src/components/**/*.stories.@(js|jsx|ts|tsx)"],
  addons: ["@storybook/addon-links", "@storybook/addon-essentials", "@storybook/addon-interactions"],
  framework: {
    name: "@storybook/react-webpack5",
    options: {},
  },
  docs: {
    autodocs: "tag",
  },
};
export default config;


-------------------


<script src="https://unpkg.com/image-compare-viewer/dist/image-compare-viewer.min.js" /></script>

<link href="https://unpkg.com/image-compare-viewer/dist/image-compare-viewer.min.css" rel="stylesheet" type="text/css" />

<div id="image-compare">
<img src="mael-before.jpg" alt="" style="max-width: none; height: 100%;" />
<img src="mael-after.jpg" alt="" style="max-width: none; height: 100%;" />
</div>

<script>
const element = document.getElementById("image-compare");
const viewer = new ImageCompare(element).mount();
</script>
ChatGPT
