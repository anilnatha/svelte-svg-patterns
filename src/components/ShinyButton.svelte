<script>
  import lang from "../routes/_lang.js";
  let strings = lang.strings;
</script>

<a
  href="https://pro.pattern.monster/pricing"
  target="_blank"
  title="Pattern Monster Pro"
  class="shiny">{strings.upgradePro}</a
>

<style>
  .shiny {
    display: grid;
    place-content: center;
    background: gold;
    color: black;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
    background: linear-gradient(
      -45deg,
      gold 50%,
      rgb(255, 249, 215) 60%,
      gold 70%
    );
    background-size: 600% 100%;
    animation: shine 20s infinite;
    animation-delay: 0s;
    animation-timing-function: linear;
    padding: 0.5rem 0.8rem;
    border-radius: 0.75rem;
    overflow: hidden;
    height: 2.6rem;
    font-size: 0.9rem;
    font-weight: 600;
  }

  @keyframes shine {
    0% {
      background-position-x: 400%;
    }
    50% {
      background-position-x: 0%;
    }
    100% {
      background-position-x: -400%;
    }
  }
</style>
