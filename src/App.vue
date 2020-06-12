<template>
  <div id="app">
    <notes></notes>
  </div>
</template>

<script>
import MyNotes from './components/notes.vue';

export default {
  name: 'App',
  components: {
    notes: MyNotes,
  }
}
</script>
<style>
#app {
    margin: 50px 15px 15px 50px;
    padding: 50px 50px 15px 50px;
    background-color: rgb(160, 235, 253);
    color: rgb(0, 136, 136);
    font-size: large;
    font-weight: 600;
    border-radius: 30px;
    align-content: center;

}

div label {
    float: left;
    width: 40%;
}

.knopka {
    margin: 15px 15px 15px 0px;
    width: 40%;
    border: 17px;
    padding: 5px 10px;
    border: 2px solid;

    background:#eee;
    color:#088;
    text-decoration:none;
    display:block;
    width:120px;
    text-align:center;
    margin:20px auto;
    padding:10px 10px;
    transition:all 0.3s;
    font-size: large;
}
.knopka:hover {
    box-shadow:0px -5px 0 #088 inset;
}
.book {
    border-radius: 5px;
    background-color: rgb(255, 255, 255);
}

#button-change {
    background-color: #eee;
    color: #088;
    font-size: large;
    margin: 10px 10px 10px 10px;
    width: 10%;
    height: 40px;
    border: 10px;
    padding: 5px 10px;
    border: 2px solid;
}
#button-change:hover {
    box-shadow:0px -5px 0 #088 inset;
}

#button-delete {
    background-color: #088;
    color: #eee;
    font-size: large;
    margin: 10px 10px 10px 10px;
    width: 10%;
    height: 40px;
    border: 10px;
    padding: 5px 10px;
    border: 2px solid;
}
#button-delete:hover {
    box-shadow:0px -5px 0 rgb(190, 190, 190) inset;
}

</style>
