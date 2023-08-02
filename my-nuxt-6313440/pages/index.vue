<template>
    <div>
        <h2>4 Queens of T-Pop</h2>
        <div class="row"> 
            <div class = "column">
                <div class="card">
                    <a href="/Bowkylion"><img src="~/assets/img/Bowkylion.png" alt=""></a>
                    <a href="/Bowkylion">Bowkylion</a>
                </div>
            </div>
            <div class="column">
                <div class="card">
                    <a href="/Inkwaruntorn"><img src="~/assets/img/Inkwaruntorn.png" alt=""></a>
                    <a href="/Inkwaruntorn">Inkwaruntorn</a>
                </div>
            </div>
            <div class="column">
                <div class="card">
                    <a href="/Violettewautier"><img src="~/assets/img/Violettewautier.png" alt=""></a>
                    <a href="/Violettewautier">Violettewautier</a>
                </div>
            </div>
            <div class="column">
                <div class="card">
                    <a href="/Zommarie"><img src="~/assets/img/Zommarie.png" alt=""></a>
                    <a href="/Zommarie">Zommarie</a>
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