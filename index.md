---
layout: page
title: There is No Plan Bee Without Them
---

# Imports and Exports

We will explain everything in due time.

{% raw %}
<div class="slidecontainer">
    <input type="range" min="1" max="3" value="2" class="slider" id="myRange">
    <p>Value: <span id="demo"></span></p>
    <script>
      var slider = document.getElementById("myRange");
      var output = document.getElementById("demo");
      output.innerHTML = slider.value;

      slider.oninput = function() {
          output.innerHTML = this.value;
      }
  </script>
</div>
{% endraw %}

# Beehives and Honey Production
