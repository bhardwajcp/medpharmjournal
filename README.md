<div id="visit-counter" style="display:none;">0</div>

<script>
// Simple hidden counter system
let visits = localStorage.getItem("mySiteCounter") || 0;
visits = parseInt(visits) + 1;
localStorage.setItem("mySiteCounter", visits);

// You (as host) can view it by inspecting DOM
document.getElementById("visit-counter").innerText = visits;
</script>
