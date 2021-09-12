<template>
  <div class="calc">
  <div class="display">123.20</div>
  <div class="btn clear">C</div>
  <div class="btn operator">%</div>
  <div class="btn">7</div>
  <div class="btn">8</div>
  <div class="btn">9</div>
  <div class="btn operator">/</div>
  <div class="btn">4</div>
  <div class="btn">5</div>
  <div class="btn">6</div>
  <div class="btn operator">x</div>
  <div class="btn">1</div>
  <div class="btn">2</div>
  <div class="btn">3</div>
  <div class="btn operator">-</div>
  <div class="btn">0</div>
  <div class="btn">.</div>
  <div class="btn">=</div>
  <div class="btn operator">+</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    *{
    background: #111;
    }
    .calc {
        width: 400px;
        margin: 0 auto;
        font-size: 40px;
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        grid-auto-rows:minmax(auto,auto);
        border: 20px groove #999;
    }
    .display {
        grid-column: 1/5;
        background: #333;
        color: #fff;
        padding: 20px;
        text-align: right;
    }
    .clear {
        grid-column: 1/4;

    }
    .btn {
        padding: 10px;
        background: linear-gradient(#fafafa, lightgray);
        border: 1px solid #999;
        cursor: pointer;

    }
    .btn:active {
        background: #777;
        color: #fff;
    }
    .operator {
        color: red;
    }
</style>