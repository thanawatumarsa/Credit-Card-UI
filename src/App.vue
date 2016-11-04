<template lang="html">
  <link href="https://fonts.googleapis.com/css?family=Archivo+Narrow" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
<div class="card">
  <div class="header">
    <div class="left">
    PAYMENT<br>
    DETAILS
    </div>
    <div class="right">
      VISA
    </div>
    </div>
    <div class="container">
    <div class="conLeft">
        CARDHOLDER'S NAME<br>
      <input type="text" name="name" value="" size="20" maxlength="24">
    </div>
    <div class="conRight">
        CARD NUMBER<br>
      <input type="text" pattern="" name="name" value="" size="25">
    </div>
      <div class="secondlineleft">
        <div class="exDate">
        EXPIRY DATE<br>
        <select name="Month">
          <option value="January">January</option>
          <option value="Fabruary">Fabruary</option>
          <option value="March">March</option>
          <option value="April">April</option>
          <option value="May">May</option>
          <option value="June">June</option>
          <option value="July">July</option>
          <option value="August">August</option>
          <option value="September">September</option>
          <option value="October">October</option>
          <option value="November">November</option>
          <option value="December">December</option>
        </select>
        <select name="Yeah" />
          <option>2009</option>
          <option>2010</option>
          <option>2011</option>
          <option>2012</option>
          <option>2013</option>
          <option>2014</option>
          <option>2015</option>
          <option>2016</option>
          <option>2017</option>
          <option>2018</option>
        </select>
      </div>
      <div class="cvv">
        CVV<br>
        <input type="text"  name="name" value="" size="16" maxlength="4">
      </div>
    </div>
  </div>
  </div>
</div>


</template>

<script>
export default {
  data () {
    return {}
  },
  computed: {},
  mounted () {},
  methods: {},
  components: {}
}
</script>

<style lang="css">
body {
  background-image: url("https://goo.gl/2hqxIp");
}
.card{
  width: 500px;
  height: 300px;
  border-radius: 25px;
  box-shadow: 5px 10px 25px 0 rgba(0,0,0,0.2);
  margin-left: 50px;
  margin-top: 50px;
  background-color: white;
  overflow: hidden;
}

.header {
  font-family: 'Archivo Narrow', sans-serif;
  font-size: 20px;
  background-color: #018FFD;
  padding: 25px 30px;
  height: 50px;
  color: white;
  font-weight: bold;
}

.container {
  padding: 20px 30px;
  font-family: 'Raleway', sans-serif;
  font-weight: bold;
  color: #8C8C8C;
  font-size: 9px;
}

input[type=text] {
  height: 18px;
  padding: 9px 10px;
  margin: 8px 0;
  border-radius: 5px;
  border: 1px solid #CFCFCF;
}

select {
  font-family: 'Raleway', sans-serif;
  font-weight: bold;
  width: 120px;
  padding: 9px 2px;
  margin: 8px 0;
  border-radius: 5px;
  border: 1px solid #CFCFCF;
  margin-right: 12px;
}

.conLeft {
  float: left;
}

.conRight {
  margin-left: 20px;
  display: inline-block;
}

.secondlineleft {
  margin-top: 15px;
  float: left;
}

.left {
  float: left;
}

.right {
  float: right;
  font-size: 45px;
}

.exDate {
  float: left;
}

.cvv {
  margin-left: 5px;
  display: inline-block;
  float: right;
}

h1 {
  margin-top: 0px;
}


</style>
