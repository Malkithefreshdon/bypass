<template>
  <div>
    <p id="electron-status">isElectron: {{ useElectron().isElectron }}</p>
    <NuxtPage />
  </div>
</template>

<style>
#electron-status {
  background: #000;
  color: #fff;
  position: absolute;
  font-size: 2rem;
  font: bold;
}
</style>
