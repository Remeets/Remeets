<p id="remets"></p>

<script>
  var name = "remets";
  var i = 0;
  var text = "";
  function typeName() {
    if (i < name.length) {
      text += name.charAt(i);
      document.getElementById("myName").innerHTML = text;
      i++;
      setTimeout(typeName, 100);
    }
  }
  typeName();
</script>
