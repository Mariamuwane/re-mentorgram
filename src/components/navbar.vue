<template>
  <div class="navBar container">
        <nav class="nav">
            <div class="logo">
                <h1>Mentorgram</h1>
            </div>
            <div class="navmenu">
                <a href="#">How it works?</a>
                <a href="#">Why Mentoring</a>
                <a href="#">For Organizations</a>
            </div>
            <div class="join-in">
                <!-- <button type="submit" class="join"></button> -->
                <a href="#" class="join" style="color: white;">Join</a>
                <a href="#">Log In</a>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
  name: 'navbar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .nav{
    position: relative;
    overflow:hidden;
    /* background-color: #DBFFE4; */
    margin-top:50;
}
.nav a{
    float: left;
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 15px;
    font-weight:bold;
}
.logo{
    float:left;
    margin-left: 25px;
    /* font-weight:bold; */

}
.navmenu{
    float: none;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
.main{
    padding-top:150px;
}
.image{
    padding-top:150px;
}
.join-in{
    float:right;
    position: right;
    margin-right: 1em;  
    margin-top:10px;
}
.join{
    background-color:black;
    padding:5px;
    text-align: center;
    width: 100px;
    /* border: 10px; */
    border-radius: 0px;
    justify-content:center;
    display:flex;
    
}
</style>
