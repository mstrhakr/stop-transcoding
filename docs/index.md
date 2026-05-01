---
layout: default
title: Plex Settings Help
permalink: /
---

Your Plex admin sent you here. Pick your device below and we'll walk you through a quick one-time setting change to get the best quality.

<input type="text" id="device-search" placeholder="Search for your device..." oninput="filterCards()" autocomplete="off" />

<div class="device-grid" id="device-grid">
  <a class="device-card" href="/xbox-one/">Xbox One</a>
  <a class="device-card" href="/nvidia-shield/">NVIDIA Shield</a>
  <a class="device-card" href="/android-tv/">Android TV</a>
  <a class="device-card" href="/google-tv/">Chromecast with Google TV</a>
  <a class="device-card" href="/roku/">Roku</a>
  <a class="device-card" href="/fire-tv/">Fire TV</a>
  <a class="device-card" href="/apple-tv/">Apple TV</a>
</div>

<script>
function filterCards() {
  var q = document.getElementById('device-search').value.toLowerCase();
  document.querySelectorAll('.device-card').forEach(function(card) {
    card.style.display = card.textContent.toLowerCase().indexOf(q) > -1 ? '' : 'none';
  });
}
</script>
