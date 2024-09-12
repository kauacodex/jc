<style>
@keyframes gradient {
  0% { background: linear-gradient(45deg, #ff0000, #0000ff); }
  50% { background: linear-gradient(45deg, #00ff00, #ff00ff); }
  100% { background: linear-gradient(45deg, #ff0000, #0000ff); }
}
body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(45deg, #ff0000, #0000ff);
  animation: gradient 10s ease infinite;
}
</style>