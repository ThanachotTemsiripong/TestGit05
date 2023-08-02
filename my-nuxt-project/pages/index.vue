<template>
    <div>
        <h2>4 Queens of K-Pop</h2>
        <div class="row"> 
            <div class = "column">
                <div class="card">
                    <a href="/Hwasa"><img src="~/assets/img/Hwasa.png" alt=""></a>
                    <a href="/Hwasa">Hwasa</a>
                </div>
            </div>
            <div class="column">
                <div class="card">
                    <a href="/Moonbyul"><img src="~/assets/img/Moonbyul.png" alt=""></a>
                    <a href="/Moonbyul">Moonbyul</a>
                </div>
            </div>
            <div class="column">
                <div class="card">
                    <a href="/Solar"><img src="~/assets/img/Solar.png" alt=""></a>
                    <a href="/Solar">Solar</a>
                </div>
            </div>
            <div class="column">
                <div class="card">
                    <a href="/Wheein"><img src="~/assets/img/Wheein.png" alt=""></a>
                    <a href="/Wheein">Wheein</a>
                </div>
            </div>

        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
    h2 {
        margin-bottom:  20px;
        font-size: 36px;
    }
    p {
        margin: 20px 0;
    }
    * {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 10px;
}

/* Remove extra left and right margins, due to padding in columns */
.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  background-color: #f1f1f1;
}

/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}
</style>