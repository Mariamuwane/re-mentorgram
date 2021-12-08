<template>
    <div class="container main">
        <main class="row">
            <div class="bodyy">
                <div class="column left">
                    <h1>We're better<br> together</h1>
                    <p>Join our free community of entrepreneurs <br>and volunteer business mentors.</p>
                    <div class="table">
                        <div class="join-explore">
                            <!-- <button type="submit" class="join"></button> -->
                            <a href="#" class="join-now" style="color: black;">Join now</a>
                            <a href="#" class="explore">Explore More</a>
                        </div>
                    </div>
                    
                </div>
            </div>
            <div class="column right">
                <img src="../assets/mentorman.jpeg" class="image">
            </div>
        </main>
        <div class="foot">
            <h2>Business Mentoring Fuels Success</h2>
        </div>
    </div>
</template>

<script>
export default {
  name: 'main',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.main{
padding-top:100px;
}
.image{
    padding-top:50px;
    height: 600px;
}

.main{
    margin: -45px 40px 0px 60px;
    /* margin-bottom: 120px; */
    
}
.main h1{
    font-size: 50px;
    font-family: "DMSerif";
    font-weight: bolder;
    font-size: 3.75rem;
}
.main p{
    line-height: 30px;
    font-family: "DMSerif";
    font-weight: bold;

}
.column {
    float: left;
    padding: 10px;
  }
  
  .left {
    width: 55%;
  }
  
  .right {
    
    width: 45%;
  }
  /* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
  }
.img{
    height: 50px;
}
/* .table{
    display: table;
} */
.join-explore{
    align-items:center;
    text-decoration: none;
    display: flex;
    font-weight: bold;
}
.join-now{
    background-color:rgb(0, 250, 154);
    padding:20px;
    text-align: center;
    width: 150px;
    text-decoration: none;
    justify-content:center;
}
.explore{
    /* background-color:rgb(185, 235, 209); */
    padding:20px;
    text-align: center;
    width: 150px;
    text-decoration: none;
    justify-content:center;
    color: black;
}
.foot{
    margin-top: 100px;
    text-align: center;
    font-weight: 900;
}
</style>