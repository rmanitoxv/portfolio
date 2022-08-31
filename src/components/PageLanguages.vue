<template>
  <div class="container">
    <div class="table">
        <div class="row">
            <div>
                C
            </div>
            <div>
                C++
            </div>
            <div>
                C#
            </div>
            <div>
                CSS
            </div>
            <div>
                Django
            </div>
        </div>
        <div class="row">
            <div>
                HTML
            </div>
            <div>
                JavaScript
            </div>
            <div>
                Laravel
            </div>
            <div>
                PHP
            </div>
            <div>
                Vue.Js
            </div>
        </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'PageHead',
  props: {
    msg: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .container{
        padding: 7.5rem;
        color: #E4E4E4;
        font-family: 'next art';
        background: #414141;
    }
    .table{
        display: flex;
        flex-direction: column;
    }
    .row{
        display: flex;
        justify-content: center;
    }
    .row div{
        background: #2A2A2A;
        box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.47);
        border-radius: 1.75rem;
        width: 10rem;
        height: 10rem;
        color: #00C4F0;
        font-size: 1.5rem;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 2.5rem;
        transition: .25s;
    }
    .row div:hover{
        background: #EFEFEF;
        color: #2A2A2A;
    }
</style>
